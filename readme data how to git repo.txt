Microsoft Windows [Version 10.0.14393]
(c) 2016 Microsoft Corporation. All rights reserved.

C:\Users\Nizam R.H Aljawabreh>cd C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code>mkdir local-repo

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code>cd local-repo

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git status
fatal: not a git repository (or any of the parent directories): .git

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git init
Initialized empty Git repository in C:/Users/Nizam R.H Aljawabreh/Desktop/cources/Writing Professional Code/local-repo/.git/

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        hello.txt

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git add hello.txt

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   hello.txt


C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git commit -m "add a new file that will eventually contain my name"
[master (root-commit) 663ed77] add a new file that will eventually contain my name
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 hello.txt

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git status
On branch master
nothing to commit, working tree clean

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   hello.txt

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git add hello.txt

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git commit -m "add my name to hello.txt"
[master 62e9471] add my name to hello.txt
 1 file changed, 1 insertion(+)

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>
C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git log
commit 62e947135566ee7f0541c92b8e07be94dabbe8f1 (HEAD -> master)
Author: nizamra_95@hotmail.com <nizamra_95@hotmail.com>
Date:   Thu Jan 17 15:24:56 2019 +0200

    add my name to hello.txt

commit 663ed779db0e29faab8964bad1c470564b888db0
Author: nizamra_95@hotmail.com <nizamra_95@hotmail.com>
Date:   Thu Jan 17 15:00:45 2019 +0200

    add a new file that will eventually contain my name

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>