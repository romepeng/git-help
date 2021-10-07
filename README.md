# git-help

git can use github.com and gitee.com

教程：廖雪峰Git教程 https://www.liaoxuefeng.com/wiki/896043488029600

Install:
sudo apt install git

git --help

git remote --help
git branch --help

Config:
ssh -T git@github.com
git config --list

git config --global user.name "romepeng"
git config --global user.email "romepeng@outlook.com"

copy ssh-pub-key to github.com/setup/ssh/add


Useage:
git clone git@github.com:romepeng/git-help.git
don't use https ,use ssh !!!

cd git-help

git init
git add .
git commit -m "first commit"
git status

git branch -M main
git remote add origin git@github.com:romepeng/git-help.git
git remote -v
git remote rm origin

git push -u origin main

???
master and main diff?
gitee.com don't push to master,
push to main branch ok.

Use proxychains4 proxy:
proxychains4 git ...
need clash and proxy jd.


Same to gitee.com
copy ssh-key ;
ssh -T git@gitee.com
git remote add origin-gitee git@gitee.com:romepeng/git-help.git
git push -u origin-gitee master






