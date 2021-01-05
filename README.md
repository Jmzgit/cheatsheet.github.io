# Github Cheat Sheet

Remote to Local  
open new Repot in Github  
<copy url>  
open new folder in Local  
  $ mkdir <name>  
Add remote Repo to Local folder - use fetch flag -f  
  $ git remote add -f <name> <Remote git url>  
Confirm remote added  
  $ git remote --v  
Check branch - always be on same branch as Remote usually main > main  
  $ git branch  
Push upstream Local to Remote  
  $ git push --set-upstream <name> <Remote branch>  
  
### Git Revert to history of commit
$ git revert --no-edit HEAD~20..

### git revert --no-edit <hash of commit>..HEAD
$ git revert --no-edit 97fe90437173f6a5c855263bc389e7f2e23bff61..HEAD

### git revert --no-edit HEAD~<number to walk back on commit history>..
$ git revert --no-edit HEAD~5..

### After revert action:
$ git log // this to check new commit title  
$ git push //this to send to remote  
