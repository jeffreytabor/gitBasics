# Git Basics
Overview for a specific share project

---
###### show overview and outstanding tasks
```
git status
```
---
###### Create a branch to work on a new feature
###### (Note: a branch can be created from a branch.)
```
git branch descriptiveBranchName
```
---
###### Start using a branch.
###### (Note: there will be only one copy of the folder structure on your computer, by checking out a branch, it uses, "Context Switching" to modify the same files without touching the other versions that live in the same path of the folder structure.)
###### (Note: switching to a new branch without commiting will warn you of losing changes first.)
###### (Note: You can switch to a new branch if things are, "Mostly Clean", meaning a new file has been created but not commited. The new file will just show up after switching to the new branch.)
```
git checkout descriptiveBranchName
```
---
###### display branches, with Asterix by branch in use.
```
git branch
```
---
###### Add and commit the files that have changed with a message.
```
git add index.php
git commit -m "Details about this stopping point."
```
---
###### Or, add all changed files and commit with one command.
```
git commit -am "Details about this stopping point."
```
---
###### To checkout and swtich to a branch in one command.
```
git checkout -b descriptiveBranchName
```
---
###### To see all changes in local branches.
###### (Note: This can be done through the GUI.)
```
git log --graph --oneline --decorate --all
```
---
###### To find the differences between any two braches.
```
git diff branchOne..branchTwo
```
---
###### Find the differences between two branches on one line.
```
git diff -color-words branchOne..branchTwo
```
---
###### Find branches that can be deleted because they are up to date with currently checked out branch.
```
git branch --merged
```
---
###### A more descriptive showing of why we branched.
```
git branch -m branchOne branchTwo
```
---
###### To remove a branch.
###### (Note: the --delete flag can be used in place of the -d flag.)
```
git branch -d branchOne
```
---
###### 
```

```
---
###### 
```

```
---
###### 
```

```
---
###### 
```

```
---
###### 
```

```

