# Reference_Docs

Command to push a newly created branch from local system to github using gitbash

$ git push –set-upstream origin new-branch

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

to push an existing GIT repository from local system to github through command line

git remote add origin https://github.com/abhishek356/FirstHibernateProject.git
git branch -M main
git push -u origin main

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

to push an existing repo on local system and then push it for the first time to github
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/abhishek356/MVC.git
git push -u origin main

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

aks21@LAPTOP-3GJREQE0 MINGW64 /c/users/aks21/eclipse-workspace/CrioProject (main)
$ git push -u origin main
To https://github.com/abhishek356/CrioProject.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/abhishek356/CrioProject.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

aks21@LAPTOP-3GJREQE0 MINGW64 /c/users/aks21/eclipse-workspace/CrioProject (main)
$ ^C

aks21@LAPTOP-3GJREQE0 MINGW64 /c/users/aks21/eclipse-workspace/CrioProject (main)
$ git pull --rebase origin master
fatal: couldn't find remote ref master

aks21@LAPTOP-3GJREQE0 MINGW64 /c/users/aks21/eclipse-workspace/CrioProject (main)
$ git pull --rebase origin main
From https://github.com/abhishek356/CrioProject
 * branch            main       -> FETCH_HEAD
Successfully rebased and updated refs/heads/main.

aks21@LAPTOP-3GJREQE0 MINGW64 /c/users/aks21/eclipse-workspace/CrioProject (main)
$ git push -u origin main
Enumerating objects: 48, done.
Counting objects: 100% (48/48), done.
Delta compression using up to 16 threads
Compressing objects: 100% (30/30), done.
Writing objects: 100% (47/47), 7.12 KiB | 729.00 KiB/s, done.
Total 47 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/abhishek356/CrioProject.git
   eee2b64..792057b  main -> main
branch 'main' set up to track 'origin/main'.

