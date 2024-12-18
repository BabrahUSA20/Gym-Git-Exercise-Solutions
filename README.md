# GIT Exercises Projects
# Bunddle 1  
# Exercise 1
This first exercise will be covering the basics.

```bash
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % ls
README.md
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git init
Initialized empty Git repository in /Users/gymicyerekezo/GitExerciseSolu/.git/
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md

nothing added to commit but untracked files present (use "git add" to track)
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git add README.md
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git status       
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md

gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git commit -m "initial commit"
[master (root-commit) 8ce51a9] initial commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git branch -M main
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git remote add origin https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git branch        
* main
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git checkout master

error: pathspec 'master' did not match any file(s) known to git.
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git branch         
* main
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git branch -m main master
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git branch               
* master
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git branch -m  master main
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git branch                
* main
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git status
On branch main
nothing to commit, working tree clean
gymicyerekezo@icyerekezos-iMac GitExerciseSolu % git pull  
warning: no common commits
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), done.
From https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions
 * [new branch]      main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main
gymicyerekezo@icyerekezos-iMac Gym-Git-Exercise-Solutions % git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
gymicyerekezo@icyerekezos-iMac Gym-Git-Exercise-Solutions % git branch     
* main
gymicyerekezo@icyerekezos-iMac Gym-Git-Exercise-Solutions % git push origin main                           
Everything up-to-date
gymicyerekezo@icyerekezos-iMac Gym-Git-Exercise-Solutions % ls
README.md
gymicyerekezo@icyerekezos-iMac Gym-Git-Exercise-Solutions % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
gymicyerekezo@icyerekezos-iMac Gym-Git-Exercise-Solutions % git add . 
gymicyerekezo@icyerekezos-iMac Gym-Git-Exercise-Solutions % git commit -m "Updated readme"  

[main 5c75ddf] Updated readme
 1 file changed, 69 insertions(+), 1 deletion(-)
 rewrite README.md (100%)
gymicyerekezo@icyerekezos-iMac Gym-Git-Exercise-Solutions % git push origin main          
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.08 KiB | 1.08 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
   6b986f0..5c75ddf  main -> main
gymicyerekezo@icyerekezos-iMac Gym-Git-Exercise-Solutions % 
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch
* dev
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch
* dev
  main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch  ev     
* dev
  main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch dev   
fatal: a branch named 'dev' already exists
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch -c test
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch       
* dev
  main
  test
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions>
                                              git checkout test
Switched to branch 'test'
Your branch is up to date with 'origin/main'.
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch       
  dev
  main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/main'.
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch
* dev
  main
  test
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch -d test
Deleted branch test (was e49fe9e).
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch
* dev
  main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions>
```
# Exercise 2
```bash
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git commit -m "this readme" 
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git status
On branch main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git status       
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        home.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash list 
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git add .
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git status     
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html

PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash list
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git add team.html
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash list   
stash@{0}: WIP on main: 04634cd this readme
stash@{1}: WIP on main: 04634cd this readme
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash        
Saved working directory and index state WIP on main: 04634cd this readme
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash list
stash@{0}: WIP on main: 04634cd this readme
stash@{1}: WIP on main: 04634cd this readme
stash@{2}: WIP on main: 04634cd this readme
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash list
stash@{0}: WIP on main: 04634cd this readme
stash@{1}: WIP on main: 04634cd this readme
stash@{2}: WIP on main: 04634cd this readme
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash pop stash@{1}
error: unknown switch `e'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --[no-]quiet      be quiet, only report errors
    --[no-]index          attempt to recreate the index

PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash pop "stash@{1}"
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html

Dropped stash@{1} (77273d34c7e33e3a3cfb5c862d55669c33765f86)
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash list           
stash@{0}: WIP on main: 04634cd this readme
stash@{1}: WIP on main: 04634cd this readme
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash pop "stash@{1}"
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (6791c7b45f51bc2d8eabd46d565a21d108dea520)

PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git add .
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git commit -m "Commited the current changes and read to be pushed" 
[main 846e503] Commited the current changes and read to be pushed
 3 files changed, 103 insertions(+), 5 deletions(-)
 create mode 100644 about.html
 create mode 100644 home.html
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.16 KiB | 297.00 KiB/s, done.    
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)  
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
   04634cd..846e503  main -> main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git reset         
Unstaged changes after reset:
M       README.md
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git reset
Unstaged changes after reset:
M       README.md
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> 
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> 
```
# Bundle 2
# Exercise 1
```bash 
    --[no-]ignore-other-worktrees
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch
olutions> git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch
  dev
* ft/bundle-2
  main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> touch service.html
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> mv .\service.html services.html
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git add .
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git commit -m "service ready to be pushed"
[ft/bundle-2 51eba34] service ready to be pushed
 1 file changed, 11 insertions(+)
 create mode 100644 services.html
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 468 bytes | 468.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git add .
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git commit -m "ready to push readme"      
[ft/bundle-2 5cd92d1] ready to push readme
 1 file changed, 38 insertions(+)
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch                                
  dev
* ft/bundle-2
  main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch main
fatal: a branch named 'main' already exists
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch     
  dev
* ft/bundle-2
  main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git checkout main 
error: Your local changes to the following files would be overwritten by checkout:
        README.md
Please commit your changes or stash them before you switch branches.
Aborting
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch       
  dev
* ft/bundle-2
  main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git status
On branch ft/bundle-2
Your branch is ahead of 'origin/ft/bundle-2' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        README.md
Please commit your changes or stash them before you switch branches.
Aborting
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> get reset
get : The term 'get' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the 
name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ get reset
+ ~~~
    + CategoryInfo          : ObjectNotFound: (get:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git status       
On branch ft/bundle-2
Your branch is ahead of 'origin/ft/bundle-2' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git reset 
Unstaged changes after reset:
M       README.md
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git status
On branch ft/bundle-2
Your branch is ahead of 'origin/ft/bundle-2' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        README.md
Please commit your changes or stash them before you switch branches.
Aborting
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git commit "reseting"
error: pathspec 'reseting' did not match any file(s) known to git
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git commit -m "reseting"
On branch ft/bundle-2
Your branch is ahead of 'origin/ft/bundle-2' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git status              
On branch ft/bundle-2
Your branch is ahead of 'origin/ft/bundle-2' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git reset README.md     
Unstaged changes after reset:
M       README.md
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git checkout main       
error: Your local changes to the following files would be overwritten by checkout:
        README.md
Please commit your changes or stash them before you switch branches.
Aborting
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash          
Saved working directory and index state WIP on ft/bundle-2: 5cd92d1 ready to push readme
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git stash list   
stash@{0}: WIP on ft/bundle-2: 5cd92d1 ready to push readme
stash@{1}: WIP on main: 846e503 Commited the current changes and read to be pushed
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git checkout main  
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> git branch
  dev
  ft/bundle-2
* main
PS C:\Users\rurmi\Gym-Git-Exercise-Solutions> 
```
