# Git

//Unstage the file 
git reset "fileName"

//Push specific branch in remote repository (It use first time )
git push --set --upstream origin master

//Then use 
git push -u origin branch name

//Delete file from local repository 
git rm "file Name"

//Delete file in remote repostory 
1- git rm --cached "fileName"
2- git commit -m "msg"
3- git push -u origin Branch

//Bring back that file after delete in local repository (it just give delete file)
git reset --hard HEAD