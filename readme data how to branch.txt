
C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git branch
* master

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git checkout -b new-feature
Switched to a new branch 'new-feature'

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>
C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git branch
  master
* new-feature

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>abc > new-feature-file.txt
'abc' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git add new-feature-file.txt

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>
C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git status
On branch new-feature
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   new-feature-file.txt


C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git commit -m "add new file"
[new-feature f1109d8] add new file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 new-feature-file.txt

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>
C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git checkout master
Switched to branch 'master'

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>dir
 Volume in drive C has no label.
 Volume Serial Number is 50A8-3886

 Directory of C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo

17/01/2019  15:52    <DIR>          .
17/01/2019  15:52    <DIR>          ..
17/01/2019  15:05                25 hello.txt
               1 File(s)             25 bytes
               2 Dir(s)  51,071,062,016 bytes free

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git checkout new-feature
Switched to branch 'new-feature'

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>dir
 Volume in drive C has no label.
 Volume Serial Number is 50A8-3886

 Directory of C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo

17/01/2019  15:54    <DIR>          .
17/01/2019  15:54    <DIR>          ..
17/01/2019  15:05                25 hello.txt
17/01/2019  15:54                 0 new-feature-file.txt
               2 File(s)             25 bytes
               2 Dir(s)  51,071,127,552 bytes free

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git checkout master
Switched to branch 'master'

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git status
On branch master
nothing to commit, working tree clean

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git branch --no-merged
  new-feature

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git merge --no-ff new-feature -m "merge new-feature branch"
Merge made by the 'recursive' strategy.
 new-feature-file.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 new-feature-file.txt

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>
C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>dir
 Volume in drive C has no label.
 Volume Serial Number is 50A8-3886

 Directory of C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo

17/01/2019  15:56    <DIR>          .
17/01/2019  15:56    <DIR>          ..
17/01/2019  15:05                25 hello.txt
17/01/2019  15:56                 0 new-feature-file.txt
               2 File(s)             25 bytes
               2 Dir(s)  51,071,115,264 bytes free

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>git branch -D new-feature
Deleted branch new-feature (was f1109d8).

C:\Users\Nizam R.H Aljawabreh\Desktop\cources\Writing Professional Code\local-repo>