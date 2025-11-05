# Demo2_1_OS_MutiTasks

# create a new repository on the command line
$ echo "# Demo2_1_OS_MutiTasks" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M master
$ git remote add origin https://github.com/wenchm/Demo2_1_OS_MutiTasks.git

$ git remote -v
origin  https://github.com/wenchm/Demo2_1_OS_MutiTasks.git (fetch)
origin  https://github.com/wenchm/Demo2_1_OS_MutiTasks.git (push)

$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 433 bytes | 216.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/wenchm/Demo2_1_OS_MutiTasks.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

# push an existing repository from the command line
$ git remote add origin https://github.com/wenchm/Demo2_1_OS_MutiTasks.git
$ git branch -M main
$ git push -u origin main
