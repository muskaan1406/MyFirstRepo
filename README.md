# MyFirstRepo
**Git notes**
On ubuntu machine
check git status
git --version
try exploring commands like echo/ touch/mkdir/vi/cat
clone the GitHub repository on to local machine
trying creating the files and data inside the files in the  local host cloned repository
this wont effect the actual repository on GitHub
After creating the files
try git add command
then git commit command 
git add file1.txt
git commit -m "Added file1.txt"
which creates a snapshot
git ignore is a command which helps us to ignore few unwanted data or confidential data


rootuser@DESKTOP-KGB9HF9:~/MyFirstRepo$ git commit -a -m "Modified file1.txt"
[main ec9de04] Modified file1.txt
 1 file changed, 1 insertion(+)
rootuser@DESKTOP-KGB9HF9:~/MyFirstRepo$ ls
README.md  file1.txt  file2.txt  file3.txt
rootuser@DESKTOP-KGB9HF9:~/MyFirstRepo$ git status
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
rootuser@DESKTOP-KGB9HF9:~/MyFirstRepo$ git status
On branch main
Your branch is ahead of 'origin/main' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
rootuser@DESKTOP-KGB9HF9:~/MyFirstRepo$


