# HOMEWORK2
תחלה יצרתי ריפוזטורי חדש בגיטאב שם יצרתי קובץ רשמתי בתכו MADE IN HUB 
 אחרי זה נגשתי לקונסול ומשכתי את הפרויקט בעזרת GIT CLONE 
 amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ git clone https://github.com/amit-barda/HOMEWORK2.git
Cloning into 'HOMEWORK2'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.
וכמו שאפשר לראות זה הוריד לי את זה למחשב 
לאחר מכן נגשתי לתקייה והתחלתי לעבוד 
amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ ls -la
total 31
-rw-r--r-- 1 amit 197121 2610 Mar 24 19:59 ''$'\026\026'
-rw-r--r-- 1 amit 197121  574 Mar 24 19:59 ''$'\026\026''.pub'
drwxr-xr-x 1 amit 197121    0 Mar 24 22:04  ./
drwxr-xr-x 1 amit 197121    0 Mar 24 21:24  ../
drwxr-xr-x 1 amit 197121    0 Mar 24 21:09  .git/
-rw-r--r-- 1 amit 197121   21 Mar 24 19:30  1.txt
drwxr-xr-x 1 amit 197121    0 Mar 24 22:04  HOMEWORK2/
-rw-r--r-- 1 amit 197121   43 Mar 24 21:27 'קישור לGIT .txt'
-rw-r--r-- 1 amit 197121 4463 Mar 24 21:25 'שיעורי בית 1 GIT .txt'

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ cd ~/Desktop/homework/HOMEWORK2/

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework/HOMEWORK2 (main)
$ ls -la
total 10
drwxr-xr-x 1 amit 197121  0 Mar 24 22:04 ./
drwxr-xr-x 1 amit 197121  0 Mar 24 22:04 ../
drwxr-xr-x 1 amit 197121  0 Mar 24 22:04 .git/
-rw-r--r-- 1 amit 197121 14 Mar 24 22:04 HOMEWORKP2
-rw-r--r-- 1 amit 197121 11 Mar 24 22:04 README.md
amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework/HOMEWORK2 (main)
$ cat homeworkp2
MADE IN HUB
כאן בדקתי מה מופיע בתוך הקובץ ואחרכך הוספתי כתב ובדקתי שזה באמת התוסף 
amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework/HOMEWORK2 (main)
$ echo "made in local" >> homeworkp2

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework/HOMEWORK2 (main)
$ cat homeworkp2
MADE IN HUB
made in local

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework/HOMEWORK2 (main)
$ git add .
warning: in the working copy of 'HOMEWORKP2', LF will be replaced by CRLF the next time Git touches it

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework/HOMEWORK2 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   HOMEWORKP2


amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework/HOMEWORK2 (main)
$ git commit -m “from_pc”
[main 9015fe3] “from_pc”
 1 file changed, 1 insertion(+)

לאחר ששניתי את מה שרציתי שמרתי את מה שעשיתי והוספתי קומניט מה שנשאר לעשות זה לעלות את זה שוב לגיטאב 
amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework/HOMEWORK2 (main)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 608 bytes | 608.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/amit-barda/HOMEWORK2.git
   55b9a71..2950c2a  main -> main
בעזרת GIT PUSH הכל עלה בהצלחה 
