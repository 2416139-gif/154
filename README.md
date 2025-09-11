karth@Karthick_13106 MINGW64 ~/kar (main)
$ git branch
* main
  trail

karth@Karthick_13106 MINGW64 ~/kar (main)
$ git checkout trail
Switched to branch 'trail'
Your branch is up to date with 'origin/trail'.

karth@Karthick_13106 MINGW64 ~/kar (trail)
$ git add fig.png

karth@Karthick_13106 MINGW64 ~/kar (trail)
$ git commit -m "figma"
[trail 7ded2c3] figma
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fig.png

karth@Karthick_13106 MINGW64 ~/kar (trail)
$ git push -u origin trail
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 168.33 KiB | 14.03 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/2416139-gif/154.git
   8848736..7ded2c3  trail -> trail
branch 'trail' set up to track 'origin/trail'.

