# x1
My Git Guide

## Local Side

### 1.) create a local folder

### 2.) invoke folder initialization 

```sh
git init
```

### 3.) assign remote server alias

syntax:

git remote add <server_alias> <https://reposerver.git>

ex.
```sh
git remote add server https://github.com/gc120978levelup1/x1.git 
```

### 4.) check if the alias assignment is successfull, you know it did if you will see the server alias and its corresponding git address in the list.

ex.
```sh
git remote -v
```

### 5.) see the list of all branches in side the remote git server 

ex.
```sh
git branch -r
```

### 6.) see the list of all branches in side our local git folder  

ex.
```sh
git branch -a
```

### 7.)  invoke pulling file from the server

syntax:
git pull <server_alias> <remote_branch_to_pull>

ex.
```sh
git pull server master --allow-unrelated-histories
```

### 8.) invoke add command, to add any changes or anything

ex.
```sh
git add .
```

### 9.) commit all the changes

syntax:

git commit -m <your_commit_message>

ex.
```sh
git commit -m changed_readme_file
```

### 10.) invoke a push your local file to arrive in the remote server

syntax:

git push <server_alias> <remote_branch_to_pull>

ex.
```sh
git push server master
```

### 11.) create a new local branch
 
syntax:

git checkout -b <new_branch_to_create>

ex.
```sh
git checkout -b newbranch001
```

### 12.) delete a local branch
 
syntax:

git branch -d <ranch_name>

ex.
```sh
git branch -d branch_name
```

### 13.) cloning an existing remote repository

syntax:

git clone --recursive <https://reposerver.git>

ex.
```sh
git clone --recursive https://github.com/gc120978levelup1/x1.git 
```

