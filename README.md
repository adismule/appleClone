# appleClone repository
- Introduction to git (Evangadi class)
---
## how to setup [appClone](https://github.com/adismule/appleClone.git) repo on your local
- open your terminal(command window for windows users) on your computer
- from your terminal navigate(cd) to the local folder where you want to clone the repo 
- team's local folder path agreement ../Desktop/Evangadi/phase-3/week-1
```bash
cd Desktop/Evangadi/phase-3/week-1
```
- then to clone the repository use:
  
```github
git clone https://github.com/adismule/appleClone.git
```
---

## how to contribute to [appClone](https://github.com/adismule/appleClone.git) repository

### to contribute to appleClone project, you must create a branch and subimt a pr. Please follow the instruction below

 * create your own branch from `main` branch using either visual studio code or github
 * use `apple_<task_name>` when you create new branch
   push your branch to remote repository if created on vs code
   * use "publish branch" button on the integrated source control on vs code or
   ```git
   git branch -u origin <your_branch_name>
   ```
 * checkout your newly created branch on visual studio code
 * make the changes as needed and once code change is ready,

   * stage your change using:
   - option 1: vs code integrated source control leftside navigation
   -option 2:
   * to see all the changed file do
   ```git 
   git status
   ```
   - and to stage all files
```git
   git add .
```

- to stage selected files

```git
   git add <file_tobe_staged>
```
* commit change
```git
git commit -m <commit_message>
```
* push your change to your branch
```git 
git push
```

* always pull the latest code from main branch to your local branch before you push/merge your changes 

```git 
git pull
```

```git 
git merge main
```

```git 
git push
```
* once change is pushed go to github and create a pr(merge request)
* include one or two developers on your pr review
* once code approved reachout to a developer with merge access to merge your branch to main branch
