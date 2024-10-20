# sagars

Sagar H S@DESKTOP-HTVCVBV MINGW64 ~
$ git config --global user.name "SAGAR SHIVAPPAYYANAMATH"

Sagar H S@DESKTOP-HTVCVBV MINGW64 ~
$ git config --global user.email "sagar03sh@gmail.com"

Sagar H S@DESKTOP-HTVCVBV MINGW64 ~
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=SAGAR SHIVAPPAYYANAMATH
user.email=sagar03sh@gmail.com

Sagar H S@DESKTOP-HTVCVBV MINGW64 ~
$ cd "D:\internship git"

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git
$ git clone "https://github.com/Sagarhs12/sagars.git"
Cloning into 'sagars'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git
$ cd Sagarhs12
bash: cd: Sagarhs12: No such file or directory

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git
$ cd "D:\internship git"

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git
$ cd sagars

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (main)
$ git commit -m"add files"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (main)
$ git commit -m"first commit"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (main)
$ git checkout -b new-features
Switched to a new branch 'new-features'

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git add feature.py
fatal: pathspec 'feature.py' did not match any files

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ touch feature.py

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git add feature,py
fatal: pathspec 'feature,py' did not match any files

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git add feature.py

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git commit -m"Add new-feature implementation"
[new-features 8594215] Add new-feature implementation
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature.py

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git push origin new-feature
error: src refspec new-feature does not match any
error: failed to push some refs to 'https://github.com/Sagarhs12/sagars.git'

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git push origin new-feature
error: src refspec new-feature does not match any
error: failed to push some refs to 'https://github.com/Sagarhs12/sagars.git'

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ ^C


Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git branch
  main
* new-features

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git status
On branch new-features
nothing to commit, working tree clean

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git commit -m"Add new-feature implementation"
On branch new-features
nothing to commit, working tree clean

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git push origin new-feature
error: src refspec new-feature does not match any
error: failed to push some refs to 'https://github.com/Sagarhs12/sagars.git'

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-features)
$ git checkout -b new-feature
Switched to a new branch 'new-feature'

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-feature)
$ git push origin new-feature
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 312 bytes | 312.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'new-feature' on GitHub by visiting:
remote:      https://github.com/Sagarhs12/sagars/pull/new/new-feature
remote:
To https://github.com/Sagarhs12/sagars.git
 * [new branch]      new-feature -> new-feature

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-feature)
$ git pull origin main
From https://github.com/Sagarhs12/sagars
 * branch            main       -> FETCH_HEAD
Already up to date.

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-feature)
$ git rm feature.py
rm 'feature.py'

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-feature)
$ git commit -m "remove feature.py"
[new-feature 1d75fd6] remove feature.py
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 feature.py

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-feature)
$ git push origin new-feature
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (1/1), done.
Writing objects: 100% (2/2), 256 bytes | 256.00 KiB/s, done.
Total 2 (delta 0), reused 1 (delta 0), pack-reused 0 (from 0)
To https://github.com/Sagarhs12/sagars.git
   8594215..1d75fd6  new-feature -> new-feature

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-feature)
$

Sagar H S@DESKTOP-HTVCVBV MINGW64 /d/internship git/sagars (new-feature)
$
