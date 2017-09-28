Git is a distributed version control system.
Git is a free software distributed under GPL. 
I have create the remote repository.
Git has a mutable index called stage.
Creating a new branch is quick and simple.
#the following cmd is right to push codes from local branch to remote branch
git push origin master:refs/for/master 
#If add no local branch, it will delete the remote branch
git push origin :refs/for/dev 
