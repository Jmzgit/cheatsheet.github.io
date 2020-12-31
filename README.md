# cheatsheet
Github Cheat Sheet

### Okay

### Git Revert to history of commit
$ git revert --no-edit HEAD~20..

### git revert --no-edit <hash of commit>..HEAD
$ git revert --no-edit 97fe90437173f6a5c855263bc389e7f2e23bff61..HEAD

### git revert --no-edit HEAD~<number to walk back on commit history>..
$ git revert --no-edit HEAD~5..
