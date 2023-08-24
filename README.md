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

## Working with Branches

Branch help to create a different copy of the source code, it is usually used to test new application or feature. The command below was used to create a new branch. The -b flag help to create and change into new brach.

**`git checkout -b my-new-branch`**

<img width="242" alt="image" src="https://github.com/kalkah/GIT-PROJECT/assets/95209274/5f212227-0478-4749-8942-ae704c8381ac">

The command below was used to list the branches on the local repository.

**`git branch`**

<img width="253" alt="image" src="https://github.com/kalkah/GIT-PROJECT/assets/95209274/dce1990a-7ff3-40bf-932e-53592c51eb5d">

The command below was used to change into another exisitng branch

**`git checkout main`**

<img width="248" alt="image" src="https://github.com/kalkah/GIT-PROJECT/assets/95209274/0c44a228-dfed-41b9-8c1e-aed2525c7969">

**`git merge`** command is used to merger one branch into another branch. The command was run from the main brach that I merging master branch into.

**`git merge master`**

<img width="623" alt="image" src="https://github.com/kalkah/GIT-PROJECT/assets/95209274/41caea7e-0c03-438d-8e50-15f418596b88">

my-new-branch was deleted using the command below

**`git branch -d my-new-branch`**

<img width="271" alt="image" src="https://github.com/kalkah/GIT-PROJECT/assets/95209274/bd8ca827-34f0-4688-8139-f84034fb83ac">

## Collaboration and Remote Repositories

Github is used for collaboration remote repository. Local repository will be availble to team member and the public by hosting it on github. However, a github account need to b e created. I have done this previously.

A remote repositoty is added to the local repository using the command below

**`git remote add origin https://github.com/kalkah/LinuxPracticeProjects`**

<img width="415" alt="image" src="https://github.com/kalkah/GIT-PROJECT/assets/95209274/b700b66a-4c9f-4146-8d3f-2674247d9f19">

After making changes in my local repository, the content of my local repository is pushed into the remote repository using the command below

**`git push origin main`**

**`git clone`** command was used to download the remote repository into my local machine.

**`git clonegit clone https://github.com/kalkah/LinuxPracticeProjects.git`**

<img width="437" alt="image" src="https://github.com/kalkah/GIT-PROJECT/assets/95209274/6f10c475-74c4-4133-8d50-20fcb3cb53b4">

