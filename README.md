测试而已 哈哈哈

Welcome to Git (version 1.8.1.2-preview20130201)


Run 'git help git' to display the help index.
Run 'git help <command>' to display help for specific commands.
Administrator@CX-10675-213212 /E/Projects/hy
$ touch README.md
Administrator@CX-10675-213212 /E/Projects/hy
$ git init
Initialized empty Git repository in e:/Projects/hy/.git/
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git add README.md
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git commit -m "first commit"
[master (root-commit) 5068f8b] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git remote add origin git@github.com:twkevin/hy.git
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git push -u origin master
Enter passphrase for key '/c/Documents and Settings/Administrator/.ssh/id_rsa':

ERROR: Repository not found.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git remote add origin git@github.com:twkevin/bb.git
fatal: remote origin already exists.
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git push -u git@github.com:twkevin/bb.git master
Enter passphrase for key '/c/Documents and Settings/Administrator/.ssh/id_rsa':

Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git push -u git@github.com:twkevin/bb.git master
Enter passphrase for key '/c/Documents and Settings/Administrator/.ssh/id_rsa':

Counting objects: 3, done.
Writing objects: 100% (3/3), 206 bytes, done.
Total 3 (delta 0), reused 0 (delta 0)
To git@github.com:twkevin/bb.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from git@github.com:twkevin/b
b.git.
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git add .
warning: LF will be replaced by CRLF in common_macro_define.h.
The file will have its original line endings in your working directory.
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git commit -m "add src"
[master 736b7b6] add src
warning: LF will be replaced by CRLF in common_macro_define.h.
The file will have its original line endings in your working directory.
 6 files changed, 524 insertions(+)
 create mode 100644 common_macro_define.h
 create mode 100644 delegate.h
 create mode 100644 hi.txt
 create mode 100644 log.cpp
 create mode 100644 thread_win32.cpp
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git push master master
fatal: 'master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git remote add origin git@github.com:twkevin/bb.git
fatal: remote origin already exists.
Administrator@CX-10675-213212 /E/Projects/hy (master)
$ git push -u git@github.com:twkevin/bb.git master
Enter passphrase for key '/c/Documents and Settings/Administrator/.ssh/id_rsa':

Counting objects: 10, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (6/6), done.
Writing objects: 100% (8/8), 4.06 KiB, done.
Total 8 (delta 0), reused 0 (delta 0)
To git@github.com:twkevin/bb.git
   5068f8b..736b7b6  master -> master
Branch master set up to track remote branch master from git@github.com:twkevin/b
b.git.
Administrator@CX-10675-213212 /E/Projects/hy (master)
$