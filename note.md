## basic concept of the git
git init
git add
git status
ls
git commit -m ""
git restore from stage file
git diff
git diff catched after stached the change of on the file
git rm this is to remove the commite file from commmite
git branch to check the directerite
git branch newname 
git checkout newname
git branch -d deletename
git branch -m newname to rename the name on that 
git merge newbranche change
git branch -m oldname newbranch name 
## to rived the git history 
git log ,git show ,git shortlog,git log --oneline
## git log command time based command 
git log  --after="y-m-d"
git log --since="y-m-d"
git log --before ="y-m-d"
## git log command Author based option 
git log --author="authorname"
## git log command file index based option 
git log --folder or file name 

## the other option
git log -n
## output option 
git log --patch
git log --stat
## content based option 
git log  --grep="one key word messege of commit"
git log -S"part of the code from code for check example"
## to improve the commite messege for improvement 
git commit -m "new messege " --amend for new or recent file 
git rebase -i HEAD~n/5 the reword
git ignore
