# Git Cours

##          ================================================
##  					git config
##          ================================================
```console
blh@wiler:~$ git config credential.helper store #=> save password
blh@wiler:~$ git config --global user.name "John Doe"
blh@wiler:~$ git config --global user.email johndoe@example.com
blh@wiler:~$ git config --list
```

## 			=================================================
##						 git revert | reset	
##      	=================================================
```console
blh@wiler:~$ git log --oneline  			  #=> show commit in a compact way
blh@wiler:~$ git revert branch_name commit_id #=> go back from a given commit
```

##			=================================================
##						git branch | merge | -d
##       	=================================================

```console
blh@wiler:~$ git branch name_branch       #=> create a branch
blh@wiler:~$ git checkout -b branch_name  #=> create a branch
blh@wiler:~$ git merge name_branch
blh@wiler:~$ git branch -d branch_name
```