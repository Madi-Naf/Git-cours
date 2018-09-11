# Git Cours

##  					git config

```console
blh@wiler:~$ git config credential.helper store #=> save password
blh@wiler:~$ git config --global user.name "blh wilder"
blh@wiler:~$ git config --global user.email blh-wilder@sanschaussettes.com
blh@wiler:~$ git config --list
```

##						 git revert | reset	

```console
Iam@wilder:~$ git log --oneline  			  #=> show commit in a compact way
Iam@wilder:~$ git revert branch_name commit_id #=> go back from a given commit

```

##						git branch | merge | -d

```console
Iam@wilder:~$ git branch name_branch       #=> create a branch
Iam@wilder:~$ git checkout -b branch_name  #=> create a branch
Iam@wilder:~$ git merge name_branch
Iam@wilder:~$ git branch -d branch_name #=> remove a branch
Iam@wilder:~$ git branch -D branch_name #=> persist the removal of a branch
```
# An exemple to use Github

## 	First initialize and push a repository before working in your project

```console
Iam@widler:~$ git init  #=> initialize a repository
Iam@widler:~$ git add . #=> add all file an modification
Iam@widler:~$ git status #=> view and verificate all modification

Iam@wilder:~$ git commit -m "enter your commti here" #=> 
Iam@wilder:~$ git log #=> view all commit in this branch

Iam@wilder:~$ git remote add origin https://github.com/user_name/repo_name.git
			#=> Set a new remote and link a local project to an online repository
Iam@wilder:~$ git remote -v  #=> Verify new remote

Iam@wilder:~$ git push -u origin master
```
