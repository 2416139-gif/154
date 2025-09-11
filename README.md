karth@Karthick_13106 MINGW64 ~/kar (trail)
$ git branch jira

karth@Karthick_13106 MINGW64 ~/kar (trail)
$ git checkout jira
Switched to branch 'jira'

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git commit
On branch jira
nothing to commit, working tree clean

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git push -u origin jira
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 168.33 KiB | 12.95 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'jira' on GitHub by visiting:
remote:      https://github.com/2416139-gif/154/pull/new/jira
remote:
To https://github.com/2416139-gif/154.git
 * [new branch]      jira -> jira
branch 'jira' set up to track 'origin/jira'.

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git checkout jira
Already on 'jira'
Your branch is up to date with 'origin/jira'.

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git add jir.png

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git commit -m "jira"
[jira 25c5811] jira
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 jir.png

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git push -u origin jira
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 50.62 KiB | 10.12 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/2416139-gif/154.git
   7ded2c3..25c5811  jira -> jira
branch 'jira' set up to track 'origin/jira'.

FOR TEXT FILE:
karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git add sum-ji
fatal: pathspec 'sum-ji' did not match any files

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git add sum-ji.txt

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git commit -m "summary of jira"
[jira 7029d11] summary of jira
 1 file changed, 13 insertions(+)
 create mode 100644 sum-ji.txt

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git pull --rebase origin jira
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 1.49 KiB | 109.00 KiB/s, done.
From https://github.com/2416139-gif/154
 * branch            jira       -> FETCH_HEAD
   25c5811..04dbb89  jira       -> origin/jira
Successfully rebased and updated refs/heads/jira.

karth@Karthick_13106 MINGW64 ~/kar (jira)
$ git push -u origin jira
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 807 bytes | 403.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/2416139-gif/154.git
   04dbb89..9217ae9  jira -> jira
branch 'jira' set up to track 'origin/jira'.



