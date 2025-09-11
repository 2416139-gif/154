karth@Karthick_13106 MINGW64 ~/kar (main)
$ git branch webpage

karth@Karthick_13106 MINGW64 ~/kar (main)
$ git branch
  jira
* main
  trail
  webpage

karth@Karthick_13106 MINGW64 ~/kar (main)
$ git checkout webpage
Switched to branch 'webpage'

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git commit
On branch webpage
nothing to commit, working tree clean

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git push -u origin webpage
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 204 bytes | 204.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'webpage' on GitHub by visiting:
remote:      https://github.com/2416139-gif/154/pull/new/webpage
remote:
To https://github.com/2416139-gif/154.git
 * [new branch]      webpage -> webpage
branch 'webpage' set up to track 'origin/webpage'.

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git add 1stpage
fatal: pathspec '1stpage' did not match any files

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git 1stpage.png
git: '1stpage.png' is not a git command. See 'git --help'.

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git add 1stpage.png

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git add 2ndpage.png

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git commit -m "webpage"
[webpage 7aae8bf] webpage
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1stpage.png
 create mode 100644 2ndpage.png

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git push -u origin webpage
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 21.58 KiB | 3.60 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/2416139-gif/154.git
   8848736..7aae8bf  webpage -> webpage
branch 'webpage' set up to track 'origin/webpage'.

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git add index.html

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git add second.html

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git commit
Aborting commit due to empty commit message.

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git commit -m "program"
[webpage 775a133] program
 2 files changed, 25 insertions(+)
 create mode 100644 index.html
 create mode 100644 second.html

karth@Karthick_13106 MINGW64 ~/kar (webpage)
$ git push -u origin webpage
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 674 bytes | 224.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/2416139-gif/154.git
   7aae8bf..775a133  webpage -> webpage
branch 'webpage' set up to track 'origin/webpage'.

