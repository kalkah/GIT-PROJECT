# BASIC GIT-PROJECT

GIT PROJECT

## Initializing GIT Repository and Making Commit

git repository is initialize in the git bash terminal with the command below from my working directory

**`git init`**

<img width="401" alt="image" src="https://github.com/kalkah/GIT-PROJECT/assets/95209274/58318561-8e6f-4c07-8270-2ac9b1989897">

A file named index.txt was created with a command below

**`touch index .txt`**

The command below was used to modify the created file above.

**`echo "I am excited to make my first commit" > index.txt`**

The modification is added to the git staging area with the command below. However, **`git add .`** doesn't really affect the repository in any significant way, changes are not actually recorded until you run git commit

**`git add .`**

The changes to the index.txt file is saved using the commit command as shown below. -m flag is used to provide a commit message

**`git commit -m "initial commit"`**

<img width="482" alt="image" src="https://github.com/kalkah/GIT-PROJECT/assets/95209274/5d3b9ff2-d4c6-4853-a393-00b574149919">

