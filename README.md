Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT


Asus@LAPTOP-Q2FNVCPV MINGW64 ~
$ cd Documents

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents
$  git clone https://github.com/gabykoba/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents
$ cd belajarGIT

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-git.txt"
[Tugas-git 6dcc831] Menambahkan Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 7a1ad3c..6dcc831
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 304.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/gabykoba/belajarGIT.git
   7a1ad3c..6dcc831  main -> main

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-html.txt"
[Tugas-html c0943c8] Menambahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating 6dcc831..c0943c8
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 335 bytes | 335.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/gabykoba/belajarGIT.git
   6dcc831..c0943c8  main -> main

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-css 1bfd05b] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating c0943c8..1bfd05b
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 363 bytes | 363.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/gabykoba/belajarGIT.git
   c0943c8..1bfd05b  main -> main

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-js.txt"
[Tugas-js 09893dc] Menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating 1bfd05b..09893dc
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 294 bytes | 294.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/gabykoba/belajarGIT.git
   1bfd05b..09893dc  main -> main

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject d4ffa6b] Menambahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating 09893dc..d4ffa6b
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 322 bytes | 322.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/gabykoba/belajarGIT.git
   09893dc..d4ffa6b  main -> main

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ notepad Tugas-php.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php 6713cef] Menambahkan Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating d4ffa6b..6713cef
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/gabykoba/belajarGIT.git
   d4ffa6b..6713cef  main -> main

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject eff3c66] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 6713cef..eff3c66
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 314.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/gabykoba/belajarGIT.git
   6713cef..eff3c66  main -> main

Asus@LAPTOP-Q2FNVCPV MINGW64 ~/Documents/belajarGIT (main)
$
