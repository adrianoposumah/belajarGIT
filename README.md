Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-git)
$ nano Tugas-Git.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt
warning: in the working copy of 'Tugas-Git.txt', LF will be replaced by CRLF the next time Git touches it

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-git)
$ git commit -m "+ file Tugas Git"
[Tugas-git adc8e67] + file Tugas Git
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git merge Tugas-git
Updating abe3acd..adc8e67
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/adrianoposumah/belajarGIT.git
   abe3acd..adc8e67  main -> main

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-html)
$ nano Tugas-html.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-html)
$ git commit -m "+ file Tugas HTML"
[Tugas-html fe354ce] + file Tugas HTML
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git merge Tugas-html
Updating adc8e67..fe354ce
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 354 bytes | 354.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/adrianoposumah/belajarGIT.git
   adc8e67..fe354ce  main -> main

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-css)
$ nano Tugas-css.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-css)
$ git commit -m "+ file Tugas CSS"
[Tugas-css dc84bc1] + file Tugas CSS
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git merge Tugas-css
Updating fe354ce..dc84bc1
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 303 bytes | 303.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/adrianoposumah/belajarGIT.git
   fe354ce..dc84bc1  main -> main

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-js)
$ nano Tugas-js.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-js)
$ git commit -m "+ file Tugas JS"
[Tugas-js a07dceb] + file Tugas JS
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git merge Tugas-git
Already up to date.

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git merge Tugas-js
Updating dc84bc1..a07dceb
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git push origin main

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 311 bytes | 311.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/adrianoposumah/belajarGIT.git
   dc84bc1..a07dceb  main -> main

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-midProoject
Switched to a new branch 'Tugas-midProoject'

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-midProoject)
$ touch Tugas-midProject.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-midProoject)
$ nano Tugas-midProject.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-midProoject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-midProoject)
$ git commit -m "+ file Mid Project"
[Tugas-midProoject 8fa74bd] + file Mid Project
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-midProoject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git merge Tugas-midProoject
Updating a07dceb..8fa74bd
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/adrianoposumah/belajarGIT.git
   a07dceb..8fa74bd  main -> main

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-php)
$ nano Tugas-php.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-php)
$ git commit -m "+ file Tugas PHP"
[Tugas-php d5740e3] + file Tugas PHP
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-php.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git merge Tugas-php
Updating 8fa74bd..d5740e3
Fast-forward
 Tugas-php.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-php.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/adrianoposumah/belajarGIT.git
   8fa74bd..d5740e3  main -> main

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-finalProject)
$ nano Tugas-finalProject.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git commit -m "+ file Final Project"
[Tugas-finalProject 20ac5d1] + file Final Project
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git merge Tugas-finalProject
Updating d5740e3..20ac5d1
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

AdriPsmh@Adriano MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 321 bytes | 321.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/adrianoposumah/belajarGIT.git
   d5740e3..20ac5d1  main -> main

