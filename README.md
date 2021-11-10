DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ git commit -m "added index.html | modified test1.txt"
[master de13e60] added index.html | modified test1.txt
 2 files changed, 2 insertions(+), 10 deletions(-)
 create mode 100644 index.html

DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ git status
On branch master
nothing to commit, working tree clean

DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ ^C

DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ echo "# Repo2" >> README.md

DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ git init
Reinitialized existing Git repository in C:/Users/DELL/Desktop/MyProject/.git/

DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ git add README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

DELL@DESKTOP-UQS32EJ MINGW64 ~/Desktop/MyProject (master)
$ git commit -m "first commit"
[master 33d9466] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
