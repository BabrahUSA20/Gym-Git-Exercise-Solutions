# GIT Exercises Projects
# Bunddle 1 
This first exercise will be covering the basics.

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
