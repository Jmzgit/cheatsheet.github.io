## Okay

# cheatsheet

Github Cheat Sheet

####  Github Cheat Sheet
#### Remote to Local
open new Repot in Github
<copy url>

#### open new folder in Local    
	$ mkdir <name>  

 #### initiate git tracking
	$ git init

#### Add remote Repo to Local folder - use fetch flag -f  
	$ git remote add -f <name> <Remote git url>  
	$ git remote add -f origin <remote url>  

#### Confirm remote added  
 	$ git remote --v  

#### Check branch - always be on same branch as Remote usually main > main  
	$ git branch  

#### Push upstream Local to Remote  
	$ git push --set-upstream <name> <Remote branch>  
 	$ git push --set-upstream origin main    

####  Please specify which branch you want to merge with.  cn
See git-pull(1) for details.  

    $ git pull <remote> <branch>  
    ex: git pull <remote branch> <local branch>  
    
#### If you wish to set tracking information for this branch you can do so with:  

   $ git branch --set-upstream-to=&lt;remote&gt;/&lt;branch&lt; main  
   ex:  git branch --set-upstream-to=&lt;remote branch of remote repository&gt;/&gt;name of local branch&lt;  

#### Git Revert to history of commit
	$ git revert --no-edit HEAD~20..

#### git revert --no-edit <hash of commit>..HEAD
	$ git revert --no-edit 97fe90437173f6a5c855263bc389e7f2e23bff61..HEAD

#### git revert --no-edit HEAD~<number to walk back on commit history>..
	$ git revert --no-edit HEAD~5..

#### After revert action:

	$ git log // this to check new commit title  
	$ git push //this to send to remote  

#### In case their is a merge before the commit you wish to arrive to
	$ git revert --no-edit -m <steps back after merge> <hash>  


	git revert --no-edit HEAD~20..
### git revert --no-edit <hash of commit>..HEAD
	$ git revert --no-edit 97fe90437173f6a5c855263bc389e7f2e23bff61..HEAD
	
### git revert --no-edit HEAD~<number to walk back on commit history>..

	$ git revert --no-edit HEAD~5..

### Git remote force
	$ git remote add ok -f <remote url>

### Ubuntu encrypt & decryption
	$ gpg -c <filename>

	$ gpg  <filename>
	
#### To add text to existing file on cli  
 	$ cat >> <filename>

#### To open Atom editor on cli
	$ nano <filename>  

#### Create file with cli editor
	$ nano  

#### Escape cli text append
	$ ctrl+C

https://buddy.works/guides/first-steps-with-git

#### Create branch
	$ git checkout -b  <name>  
	
#### Check new branch  
	$ git branch  
	$ git add...  
	$ git commit...  
	
#### Now add remote branch  
	$ git remote add  <remote branch name origin?> <new branch name>  

#### Now push to new remote  
	$  git push  <new branch name>  

#### Since no remote branch with name must add  
	$ git push --set-upstream  

#### URL Target highlight phrase in page 
	https://4x4woodworking.com/?page_id=457//#:~:text=woodworking4x4%40gmail.com
