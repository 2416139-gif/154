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

