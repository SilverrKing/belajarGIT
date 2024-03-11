Daftar tugas / branch  
  1. Tugas-git  
  2. Tugas-html  
  3. Tugas-css  
  4. Tugas-js  
  5. Tugas-midProject  
  6. Tugas-php
  7. Tugas-finalProject

Daftar perintah GIT  
...

krisk@DESKTOP-JS4BBD9 MINGW64 ~
$ cd GithubLatihan
bash: cd: GithubLatihan: No such file or directory

krisk@DESKTOP-JS4BBD9 MINGW64 ~
$ cd /c/GithubLatihan

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan
$ cd belajarGIT

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ gitt add Tugas-git.txt
bash: gitt: command not found

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git init
Reinitialized existing Git repository in C:/GithubLatihan/belajarGIT/.git/

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git add Tugas-git.txt
fatal: pathspec 'Tugas-git.txt' did not match any files

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git branch
* main

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-git)
$ nano Tugas-git.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the next time Git touches it

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'krisk@DESKTOP-JS4BBD9.(none)')

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-git)
$ git config user.email "kriskerry1725@gmail.com"

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-git)
$ git config user.name "SilverrKing"

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git f9f8b9e] Menambahkan file Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-git
Updating 205850e..f9f8b9e
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/SilverrKing/belajarGIT.git
   205850e..f9f8b9e  main -> main

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ git rm Tugas-html
fatal: pathspec 'Tugas-html' did not match any files

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ git rm Tugas-html.txt
fatal: pathspec 'Tugas-html.txt' did not match any files

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git branch -d Tugas-html
Deleted branch Tugas-html (was f9f8b9e).

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-html.txt
Switched to a new branch 'Tugas-html.txt'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html.txt)
$ touch Tugas-html.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html.txt)
$ nano Tugas-html.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html.txt)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html.txt)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html.txt c55bf0c] Menambahkan file Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html.txt)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-html
merge: Tugas-html - not something we can merge

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-html
merge: Tugas-html - not something we can merge

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-html
merge: Tugas-html - not something we can merge

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git branch -d Tugas-html.txt
error: the branch 'Tugas-html.txt' is not fully merged
hint: If you are sure you want to delete it, run 'git branch -D Tugas-html.txt'
hint: Disable this message with "git config advice.forceDeleteBranch false"

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git branch -d Tugas-html.txt
error: the branch 'Tugas-html.txt' is not fully merged
hint: If you are sure you want to delete it, run 'git branch -D Tugas-html.txt'
hint: Disable this message with "git config advice.forceDeleteBranch false"

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git branch -D Tugas-html.txt
Deleted branch Tugas-html.txt (was c55bf0c).

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-html.txt
Switched to a new branch 'Tugas-html.txt'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html.txt)
$ git branch -D Tugas-html.txt
error: cannot delete branch 'Tugas-html.txt' used by worktree at 'C:/GithubLatihan/belajarGIT'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html.txt)
$ git branch -d Tugas-html.txt
error: cannot delete branch 'Tugas-html.txt' used by worktree at 'C:/GithubLatihan/belajarGIT'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html.txt)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git branch -D Tugas-html.txt
Deleted branch Tugas-html.txt (was f9f8b9e).

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ git branch
  Tugas-git
* Tugas-html
  main

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ git init
Reinitialized existing Git repository in C:/GithubLatihan/belajarGIT/.git/

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ nano Tugas-html.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 06c6c18] Menambahkan file Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-html
Updating f9f8b9e..06c6c18
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 342 bytes | 342.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/SilverrKing/belajarGIT.git
   f9f8b9e..06c6c18  main -> main

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-css)
$ nano Tugas-css.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 08db8e2] Menambahkan file Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt
g
krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-css
Updating 06c6c18..08db8e2
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 367 bytes | 367.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/SilverrKing/belajarGIT.git
   06c6c18..08db8e2  main -> main

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-js)
$ touch Tugas-js.txt
nano
krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-js)
$ nano Tugas-js.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-js)
$ git add Tugas-git.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js f7ab0e4] Menambahkan file Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-js
Updating 08db8e2..f7ab0e4
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SilverrKing/belajarGIT.git
   08db8e2..f7ab0e4  main -> main

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt
na
krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-midProject)
$ nano Tugas-midProject.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 0e871a9] Menambahkan file Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
gi
krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-midProject
Updating f7ab0e4..0e871a9
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt
g
krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SilverrKing/belajarGIT.git
   f7ab0e4..0e871a9  main -> main

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-php)
$ nano Tugas-php.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 9d93378] Menambahkan file Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-php
Updating 0e871a9..9d93378
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SilverrKing/belajarGIT.git
   0e871a9..9d93378  main -> main

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-finalProject)
$ nano Tugas-finalProject.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 99960c8] Menambahkan file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 9d93378..99960c8
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

krisk@DESKTOP-JS4BBD9 MINGW64 /c/GithubLatihan/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 312 bytes | 312.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/SilverrKing/belajarGIT.git
   9d93378..99960c8  main -> main
