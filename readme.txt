Git is a version control system.
Git is free software.

git config --global user.name "Your Name"
git config --global user.email "email@example.com"

mkdir learngit
cd learngit
pwd

git init
//create readme.txt with notepad++
git add readme.txt
git commit -m "wrote a readme file"
git status
git diff readme.txt

git reset --hard HEAD^
git reflog
git reset --hard 92e4051

ssh-keygen -t rsa -C "youremail@example.com"
//please dig enterKey continue

git remote add origin git@github.com:flowinspace/learngit.git
git push -u origin master
//from now on,just command this express
git push origin master

git clone git@github.com:flowinspace/hello-world.git


