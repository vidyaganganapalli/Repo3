
DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   test1.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

no changes added to commit (use "git add" and/or "git commit -a")

DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ git add .
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory

DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ git commit -m "added index.html | modified test1.txt"
[master de13e60] added index.html | modified test1.txt
 2 files changed, 2 insertions(+),
