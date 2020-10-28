# BN Shell Aliases

- Write less that usual 

- Improve productivity by using these aliases

- Most commands are **`Git`** related

- Successfully tested on [**GitBash**](https://git-scm.com/downloads)

## Usage for Windows 10 users 

- Just copy/replace the **`.bashrc`** file here: /c/Users/**`$YOUR_USER_NAME`**

- For other OS and terminals you can improvise

## List of aliases:

### Terminal commands

- **`ll`** => ls -la
- **`..`** => cd ..

### Git commands

- #### Various

  - **`g`** => git 
  - **`gb`** => git branch
  - **`gd`** => git diff
  - **`gs`** => git status

- #### Add

  - **`ga`** => git add
  - **`gaa`** => git add all 

- #### Commit

  - **`gc`** => git commit -m
  - **`gcc`** => git commit -m "Update application"

- #### Push 

  - **`gp`** => git push
  - **`gpo`** => git push origin
  - **`gpom`** => git push origin master
  - **`gpod`** => git push origin develop
  
- #### Pull

  - **`gpl`** => git pull 
  - **`gplom`** => git pull origin master 
  - **`gplod`** => git pull origin develop 

- #### Checkout

  - **`gch`** => git checkout 
  - **`gchm`** => git checkout master 
  - **`gchd`** => git checkout develop 
  - **`gchb`** => git checkout -b

- #### Merge

  - **`gm`** => git merge  
  - **`gmd`** => git merge develop

- #### `Git` Remove
  
  - **`grm`** => git rm 
  - **`grmr`** => git rm -r 
  - **`grmf`** => git rm -f 
  - **`grmrf`** => git rm -rf

- #### Stash

  - **`gst`** => git stash 
  - **`gsta`** => git stash apply

- #### Stash

  - **`gl`** => git log 
  - **`glol`** => git log --oneline 

- #### Mixes of commands that are used often

  - **`gacp`** => git add -A && git commit -m "Update application" && git push 
  - **`gcmdpm`** => git checkout master && git merge develop && git push origin master 

### Others 

  - **`vue`** => winpty vue.cmd