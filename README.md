# sukanya
SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster
$ git init
Initialized empty Git repository in C:/Users/SUKANYA CHOUDHURY/OneDrive/Desktop/geekster/.git/

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster (master)
$ cd git

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ touch first.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ ls
first.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git add first.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git -status
unknown option: -status
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   first.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../test/


SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git commit -m "adding first.txt"
[master (root-commit) f96ab91] adding first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 git/first.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../test/

nothing added to commit but untracked files present (use "git add" to track)

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git log
commit f96ab91835ef9ca738ae483f6220f6c9cdb2c576 (HEAD -> master)
Author: suk-18 <suk54979@gmail.com>
Date:   Sun Jun 11 11:53:27 2023 +0530

    adding first.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ touch second.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ ls
first.txt  second.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git add second.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   second.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../test/


SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git commit -m "adding second.txt"
[master 78610bb] adding second.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 git/second.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git rm first.txt
rm 'git/first.txt'

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git add .

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git commit -m "removing first.txt"
[master d742c0d] removing first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 git/first.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git log
commit d742c0d8359ee6a2e9590ee7d768fcfdc730131c (HEAD -> master)
Author: suk-18 <suk54979@gmail.com>
Date:   Sun Jun 11 11:59:41 2023 +0530

    removing first.txt

commit 78610bbd945f4daf048f3d88d9ce13b601c692b3
Author: suk-18 <suk54979@gmail.com>
Date:   Sun Jun 11 11:57:36 2023 +0530

    adding second.txt

commit f96ab91835ef9ca738ae483f6220f6c9cdb2c576
Author: suk-18 <suk54979@gmail.com>
Date:   Sun Jun 11 11:53:27 2023 +0530

    adding first.txt

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git remote add origin https://github.com/suk-18/sukanya.git

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (master)
$ git branch -M main

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (main)
$ git push -u origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (10/10), 744 bytes | 248.00 KiB/s, done.
Total 10 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/suk-18/sukanya.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

SUKANYA CHOUDHURY@DESKTOP-CGJV960 MINGW64 ~/OneDrive/Desktop/geekster/git (main)
$
