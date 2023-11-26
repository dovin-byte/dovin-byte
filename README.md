$ cd /Users/hirayashingo/Documents/
$ mkdir hello-git-9
$ cd hello-git-9
$ pwd
/Users/hirayashingo/Documents/hello-git-9

 $ mkdir local
 $ cd local/
 $ pwd
 /Users/hirayashingo/Documents/hello-git-9/local

$ git init
Initialized empty Git repository in /Users/hirayashingo/Documents/hello-git-9/local/.git/
$ echo "# hello-github" > README.md

$ git add README.md
$ git commit -m "first commit"
[master (root-commit) 5fd9303] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
