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
# Exercise 2
```bash
rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ touch service.html

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git remote add origin https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.g
it
error: remote origin already exists.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git status
On branch ft/service-redesign
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        service.html

nothing added to commit but untracked files present (use "git add" to track)       

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git add .

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git commit -m "pushed mu service file"
[ft/service-redesign 78410f8] pushed mu service file
 1 file changed, 12 insertions(+)
 create mode 100644 service.html

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git push -u origin ft/service-redesign
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 453 bytes | 151.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:     
remote:      https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        service.html
Please commit your changes or stash them before you switch branches.
Aborting

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git add .

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git commit -m "commiting the change"
[ft/service-redesign e123e79] commiting the change
 1 file changed, 1 insertion(+), 1 deletion(-)

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        service.html

nothing added to commit but untracked files present (use "git add" to track)       

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git add .

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git commit -m "commiting the change in main branch"
[main 9d486bd] commiting the change in main branch
 1 file changed, 12 insertions(+)
 create mode 100644 service.html

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git push 
fatal: unable to access 'https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git/': Failed to connect to github.com port 443 after 21255 ms: Could not connect to server

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git push origin main
fatal: unable to access 'https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git/': Failed to connect to github.com port 443 after 21056 ms: Could not connect to server

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git remote add origin https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 466 bytes | 116.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
   9ab24f6..9d486bd  main -> main

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git add .

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git commit -m "made a change"
[main 83d149c] made a change
 1 file changed, 1 insertion(+), 1 deletion(-)

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 287 bytes | 143.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
   9d486bd..83d149c  main -> main
branch 'main' set up to track 'origin/main'.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is ahead of 'origin/ft/service-redesign' by 1 commit.
  (use "git push" to publish your local commits)

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git diff

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git diff ft/service-redesign main
diff --git a/service.html b/service.html
index d99dc0f..1a9e581 100644
--- a/service.html
+++ b/service.html
@@ -6,7 +6,7 @@
     <title>Git exercise2 | Service</title>
 </head>
 <body>
-    <h1> Welcome to my SERVICE page </h1>
+    <h1> Welcome to my SERVIce page </h1>


rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git merge main
Auto-merging service.html
CONFLICT (add/add): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign|MERGING)    
$ git status
On branch ft/service-redesign
Your branch is ahead of 'origin/ft/service-redesign' by 1 commit.
  (use "git push" to publish your local commits)

All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
        modified:   service.html


rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign|MERGING)    
$ git diff ft/service-redesign main
diff --git a/service.html b/service.html
index d99dc0f..1a9e581 100644
--- a/service.html
+++ b/service.html
@@ -6,7 +6,7 @@
     <title>Git exercise2 | Service</title>
 </head>
 <body>
-    <h1> Welcome to my SERVICE page </h1>
+    <h1> Welcome to my SERVIce page </h1>


rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git merge main
Auto-merging service.html
CONFLICT (add/add): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign|MERGING)    
$ git status
On branch ft/service-redesign
Your branch is ahead of 'origin/ft/service-redesign' by 1 commit.
  (use "git push" to publish your local commits)

All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
        modified:   service.html


rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign|MERGING)    
$ git diff ft/service-redesign main
diff --git a/service.html b/service.html
index d99dc0f..1a9e581 100644
--- a/service.html
+++ b/service.html
@@ -6,7 +6,7 @@
     <title>Git exercise2 | Service</title>
 </head>
 <body>
-    <h1> Welcome to my SERVICE page </h1>
+    <h1> Welcome to my SERVIce page </h1>
+    <h1> Welcome to my SERVIce page </h1>        


rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign|MERGING)
$ git status
On branch ft/service-redesign
Your branch is ahead of 'origin/ft/service-redesign' by 1 commit.
  (use "git push" to publish your local commits)

All conflicts fixed but you are still merging.
  (use "git commit" to conclude merge)

Changes to be committed:
        modified:   service.html


rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign|MERGING)
rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 550 bytes | 137.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
   78410f8..f7f6d29  ft/service-redesign -> ft/service-redesign

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/service-redesign)

```
# Bundle 3
# Exercise 1
```bash 

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ touch team.html

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git add .

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git commit -m "pushing team file"
[ft/team-page 864741f] pushing team file
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git remote add origin https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git push -u origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 454 bytes | 454.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions/pull/new/ft/team-page
remote:
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git log
commit 864741f4e73fdc91dbb190a2470196926bec5421 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Your Name <you@example.com>
Date:   Sun Dec 22 17:19:10 2024 +0200

    pushing team file

commit fe4eaf4e08ef042ed30072db1b2a17d056dc262d (origin/main, origin/HEAD, main, ft/contact-page)    
Author: Your Name <you@example.com>
Date:   Sun Dec 22 17:07:50 2024 +0200

    updating  the readme


rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git checkout  ft/contact-page
Switched to branch 'ft/contact-page'

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git cherry-pick 864741f4e73fdc91dbb190a2470196926bec5421
[ft/contact-page 19e4134] pushing team file
 Date: Sun Dec 22 17:19:10 2024 +0200
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git status
On branch ft/contact-page
nothing to commit, working tree clean

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git status
On branch ft/contact-page
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   team.html

no changes added to commit (use "git add" and/or "git commit -a")

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git add .

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git commit -m "added a change in contact page"
[ft/contact-page f5fef11] added a change in contact page
 1 file changed, 1 insertion(+)

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git push -u origin ft/contact-page


rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git remote add origin https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git push -u origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 696 bytes | 696.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions/pull/new/ft/contact-page      
remote:
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git branch -c ft/faq-page

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git switch ft/faq-page
Switched to branch 'ft/faq-page'
Your branch is up to date with 'origin/ft/contact-page'.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ touch faq.html

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git add .

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git commit -m "pushed faq file"
[ft/faq-page 8356904] pushed faq file
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git remote add origin https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git push -u origin ft/faq-page
fatal: unable to access 'https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git/': Failed to connect to github.com port 443 after 21233 ms: Could not connect to server

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git remote add origin https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git push -u origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 447 bytes | 447.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions/pull/new/ft/faq-page
remote:
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git revert 864741f4e73fdc91dbb190a2470196926bec5421
CONFLICT (modify/delete): team.html deleted in parent of 864741f (pushing team file) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert 864741f... pushing team file
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".
hint: Disable this message with "git config advice.mergeConflict false"

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git status
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

You are currently reverting commit 864741f.
  (fix conflicts and run "git revert --continue")
  (use "git revert --skip" to skip this patch)
  (use "git revert --abort" to cancel the revert operation)

Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add/rm <file>..." as appropriate to mark resolution)
        deleted by them: team.html

no changes added to commit (use "git add" and/or "git commit -a")

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git add .

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git commit -m "team was reverted in this faq branch"
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

You are currently reverting commit 864741f.
  (all conflicts fixed: run "git revert --continue")
  (use "git revert --skip" to skip this patch)
  (use "git revert --abort" to cancel the revert operation)

nothing to commit, working tree clean

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git status
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

You are currently reverting commit 864741f.
  (all conflicts fixed: run "git revert --continue")
  (use "git revert --skip" to skip this patch)
  (use "git revert --abort" to cancel the revert operation)

nothing to commit, working tree clean

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git push  origin ft/faq-page
Everything up-to-date

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git revert --continue
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

You are currently reverting commit 864741f.
  (all conflicts fixed: run "git revert --continue")
  (use "git revert --skip" to skip this patch)
  (use "git revert --abort" to cancel the revert operation)

nothing to commit, working tree clean

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git status
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

You are currently reverting commit 864741f.
  (all conflicts fixed: run "git revert --continue")
  (use "git revert --skip" to skip this patch)
  (use "git revert --abort" to cancel the revert operation)

nothing to commit, working tree clean

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git push -u origin ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.
Everything up-to-date

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git log --oneline
8356904 (HEAD -> ft/faq-page, origin/ft/faq-page) pushed faq file
f5fef11 (origin/ft/contact-page, ft/contact-page) added a change in contact page
19e4134 pushing team file
fe4eaf4 (origin/main, origin/HEAD, main) updating  the readme
83d149c made a change
9d486bd commiting the change in main branch
9ab24f6 Merge branch 'main' of https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions
110e969 sending my work
c2c262b Merge pull request #1 from BabrahUSA20/ft/bundle-2
51eba34 (origin/ft/bundle-2) service ready to be pushed
c6427bb updated readme
350326c updated readme

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git status
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

You are currently reverting commit 864741f.
  (all conflicts fixed: run "git revert --continue")
  (use "git revert --skip" to skip this patch)
  (use "git revert --abort" to cancel the revert operation)

nothing to commit, working tree clean

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git revert --abort

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git revert 864741f4e73fdc91dbb190a2470196926bec5421
CONFLICT (modify/delete): team.html deleted in parent of 864741f (pushing team file) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert 864741f... pushing team file
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".
hint: Disable this message with "git config advice.mergeConflict false"

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git checkout parent-of-864741f -- team.html
fatal: invalid reference: parent-of-864741f

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git log
commit 8356904b2e034ccf082f13834f5d3e3559a2684c (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Your Name <you@example.com>
Date:   Sun Dec 22 17:44:55 2024 +0200

    pushed faq file

commit f5fef114336f70fc1b0a4963a5e6db8e28e2c0a4 (origin/ft/contact-page, ft/contact-page)
Author: Your Name <you@example.com>
Date:   Sun Dec 22 17:35:21 2024 +0200

    added a change in contact page


rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git push
fatal: unable to access 'https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git/': Failed to connect to github.com port 443 after 21130 ms: Could not connect to server

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git remote add origin https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git push
fatal: unable to access 'https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git/': Failed to connect to github.com port 443 after 21102 ms: Could not connect to server

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git status
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

You are currently reverting commit 864741f.
  (fix conflicts and run "git revert --continue")
  (use "git revert --skip" to skip this patch)
  (use "git revert --abort" to cancel the revert operation)

Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add/rm <file>..." as appropriate to mark resolution)
        deleted by them: team.html

no changes added to commit (use "git add" and/or "git commit -a")

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git add .

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git commit -m "team was reverted in this faq branch"
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

You are currently reverting commit 864741f.
  (all conflicts fixed: run "git revert --continue")
  (use "git revert --skip" to skip this patch)
  (use "git revert --abort" to cancel the revert operation)

nothing to commit, working tree clean

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git push
Everything up-to-date

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git switch main
fatal: cannot switch branch while reverting
Consider "git revert --quit" or "git worktree add".

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page|REVERTING)
$ git revert --quit

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git status
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

nothing to commit, working tree clean

rurmi@Babrah MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git status
On branch ft/faq-page
Your branch is up to date with 'origin/ft/faq-page'.

nothing to commit, working tree clean

```


# Exercise 2

```bash
The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git branch
* main
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git checkout -b ft/faq-page 
Switched to a new branch 'ft/faq-page'
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git branch
* ft/faq-page
  main
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git branch
  ft/faq-page
* ft/home-page-redesign
  main
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$  git branch main
fatal: a branch named 'main' already exists
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git checkout main
M       README.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git branch
  ft/faq-page
  ft/home-page-redesign
* main
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git checkout ft/home-page-redesign
M       README.md
M       services.html
Switched to branch 'ft/home-page-redesign'
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git checkout main
M       README.md
M       services.html
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git add .
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git commit -m "pushing the change"
[main cb94860] pushing the change
 2 files changed, 9 insertions(+)
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 651 bytes | 651.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
   7cb0920..cb94860  main -> main
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git fetch origin
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git pull origin main

^C
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git pull origin main
ç^C
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git branch
  ft/faq-page
  ft/home-page-redesign
* main
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git status
On branch ft/home-page-redesign
nothing to commit, working tree clean
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git add .
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git rebase --continue
fatal: No rebase in progress?
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git push origin ft/home-page-redesign --force

^C
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git push origin ft/home-page-redesign 
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote: 
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ 

Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git add .
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git commit -m "pushing the readme file"
[main af6c1dc] pushing the readme file
 1 file changed, 86 insertions(+), 1 deletion(-)
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.02 KiB | 1.02 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
   cb94860..af6c1dc  main -> main
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git status
On branch ft/home-page-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git add .
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git commit -m "made a change to home page "
[ft/home-page-redesign 527cd25] made a change to home page
 1 file changed, 8 insertions(+)
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ git push origin ft/home-page-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 520 bytes | 520.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/BabrahUSA20/Gym-Git-Exercise-Solutions.git
   cb94860..527cd25  ft/home-page-redesign -> ft/home-page-redesign
Uruyanges-iMac:Gym-Git-Exercise-Solutions gymuruyange$ 

```

# Bunddle 5 
# Exercise 1

```bash
- On your Github repo enable Github pages
- Check if the link is publicly visible to anyone

solution 
Go to your GitHub repo:
Open your repository on GitHub (e.g., https://github.com/YourUsername/YourRepo).

Go to Settings:
At the top-right of your repo, click the "Settings" tab (it’s near the "Insights" and "Security" tabs).

Find the Pages section:
Scroll down the settings sidebar until you see "Pages" (or use https://github.com/YourUsername/YourRepo/settings/pages).

Set the branch for GitHub Pages:

Under the "Source" section, choose the branch you want to deploy from (e.g., main or gh-pages).
If you’re deploying from the main branch and your site files (like index.html) are in a specific folder (like /docs), select that folder. Otherwise, choose the root.
Click "Save".
Wait for the deployment:
GitHub will set up the Pages site. Once done, you’ll see a message like:
"Your site is published at https://YourUsername.github.io/YourRepo/"

Check public visibility:
By default, GitHub Pages are publicly accessible. Open the link and check if it’s visible. If you’re not logged into GitHub and you can still access the page, it’s public.
(Optional) Troubleshooting visibility:

Go back to Settings > General and ensure your repo is public.
If the repo is private, only users with access can see the GitHub Pages link.

for other more guidance https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

```

# Exercise 2
```bash
The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
Uruyanges-iMac:git-cafe-exercise gymuruyange$ git add index.html
Uruyanges-iMac:git-cafe-exercise gymuruyange$ git commit -m "Updated welcome message on home page"
[main f2822fc] Updated welcome message on home page
 1 file changed, 1 insertion(+), 1 deletion(-)
Uruyanges-iMac:git-cafe-exercise gymuruyange$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/BabrahUSA20/git-cafe-exercise.git
   d1d3f9c..f2822fc  main -> main
Uruyanges-iMac:git-cafe-exercise gymuruyange$ 
 


 =============
 this was done through :
 
 https://github.com/TheGymRwanda/git-cafe-exercise/pull/486

 this i main about how you pull the project from the personal 's github by " click the "Fork" button at the top-right of the page. --> Once the fork is done, you should see a new repo under your GitHub account:"and then immediately appear on your github platform and where you can clon eand edit it and immidiately see the changeon your git hub and you can also pull the request and down also you can view the change made
```