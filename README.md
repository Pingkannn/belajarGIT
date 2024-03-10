Daftar tugas / branch 
Tugas-git
Tugas-html
Tugas-css
Tugas-js
Tugas-midProject
Tugas-php
Tugas-finalProject

Daftar perintah GiT
ASUS@LAPTOP-B64L9UFN MINGW64 /
$ cd /d

ASUS@LAPTOP-B64L9UFN MINGW64 /d
$ cd users

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users
$ git clone https://github.com/Pingkannn/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users
$ Git branch Tugas-git
fatal: not a git repository (or any of the parent directories): .git

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users
$ cd belajargit

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ Git branch Tugas-git

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ touch Tugas-git.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ add .
bash: add: command not found

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git add .

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git commit -m "menambah file tugas-git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ASUS@LAPTOP-B64L9UFN.(none)')

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ Git config --global user.email cchrispiii@gmail.com

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git config --global user.name Pingkannn

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git commit -m "menambah file tugas-git.txt"
[main fdfe0dc] menambah file tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git merge Tugas-git
Already up to date.

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 312 bytes | 104.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Pingkannn/belajarGIT.git
   2788dde..fdfe0dc  main -> main

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ Git push origin main
Everything up-to-date

Daftar perintah html
ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ Git branch Tugas-html

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ touch Tugas-html.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ html add .
bash: html: command not found

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git add .

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git commit -m "menambah file tugas-html.txt"
[main f9878fa] menambah file tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git merge Tugas-html
Already up to date.

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 336 bytes | 168.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Pingkannn/belajarGIT.git
   fdfe0dc..f9878fa  main -> main

Daftar perintah css
ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ Git branch Tugas-css

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ touch Tugas-css.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git add .

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git commit -m "menambah file tugas-css.txt"
[main 88fc2de] menambah file tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git merge Tugas-css
Already up to date.

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 349 bytes | 87.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Pingkannn/belajarGIT.git
   f9878fa..88fc2de  main -> main

Daftar perintah js
ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ Git branch Tugas-js

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ touch Tugas-js.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git add .

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git commit -m "menambah file tugas-js.txt"
[main e202b9d] menambah file tugas-js.txt
 2 files changed, 2 insertions(+)
 create mode 100644 Tugas-js.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git merge Tugas-js
Already up to date.

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 152.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Pingkannn/belajarGIT.git
   88fc2de..e202b9d  main -> main

Daftar perintah midProject
ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ Git branch Tugas-midProject

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ touch Tugas-midProject.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git add .

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git commit -m "menambah file tugas-midProject.txt"
[main 4b6278d] menambah file tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git merge Tugas-midProject
Already up to date.

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 101.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Pingkannn/belajarGIT.git
   e202b9d..4b6278d  main -> main

Daftar Perintah php
ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ Git branch Tugas-php

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ touch Tugas-php.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git add .

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git commit -m "menambah file tugas-php.txt"
[main feca044] menambah file tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git merge Tugas-php
Already up to date.

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 253 bytes | 253.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Pingkannn/belajarGIT.git
   4b6278d..feca044  main -> main

Daftar Perintah finalProject
ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ Git branch Tugas-finalProject

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ touch Tugas-finalProject.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git add .

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git commit -m "menambah file tugas-finalProject.txt"
[main b7eb13e] menambah file tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git merge Tugas-finalProject
Already up to date.

ASUS@LAPTOP-B64L9UFN MINGW64 /d/users/belajargit (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 252 bytes | 252.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Pingkannn/belajarGIT.git
   feca044..b7eb13e  main -> main


       
