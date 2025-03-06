common command for git:-  

git init  
git add .  
git commit -m"give message for commit"  
git status  
git log
git log --oneline  
git checkout -b <feature name/branch name>  
git checkout main  
git merge <branch name>  
git merge --squash<branch name>  
git remote add origin https://github.com/ankit2113141/hellogit.git  
git push -u origin main  
git pull --rebase origin main  
git push origin main  
how to revert:-  
git reset --hard<hash id where we have to go > //use for linear revert  
git revert<hash no> // use to remove a particular commit by add a unmodified file which we need to commit.it is non linear  
git rebase is used to reapply commits on top of another base commit, often to keep a cleaner and more linear Git history.




 
