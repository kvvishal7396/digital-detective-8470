## 2.1 — Explore basic Terminal operation:
Operation/command used|What it does|What I Observed|
|:---|:---|:---|
|Current-directory display(PWD)|it shows us the path of the folder we are currently in|/Users/vishal102/desktop/digital-detective-8470|
|Directory listing(ls)|it lists downs all the folders and files of the current-working directory(doesn't show hidden files)|evidence			mission-01-computer-basics	mission-03-operating-system	mission-05-numbers-data		mission-07-networking		README.md
mission-00-setup		mission-02-terminal		mission-04-programs|
|Detailed listing(ls -l)|it shows all the files in the current-working directory with size and last updated date and the permisiion of files|drwxr-xr-x  2 vishal102  staff   64  6 Nov 14:25 evidence
drwxr-xr-x  3 vishal102  staff   96  6 Nov 13:46 mission-00-setup
drwxr-xr-x  3 vishal102  staff   96  6 Nov 13:46 mission-01-computer-basics
drwxr-xr-x  3 vishal102  staff   96  6 Nov 13:46 mission-02-terminal
drwxr-xr-x  3 vishal102  staff   96  6 Nov 13:46 mission-03-operating-system
drwxr-xr-x  3 vishal102  staff   96  6 Nov 13:46 mission-04-programs
drwxr-xr-x  4 vishal102  staff  128  6 Nov 13:46 mission-05-numbers-data
drwxr-xr-x  3 vishal102  staff   96  6 Nov 13:46 mission-06-git-github
drwxr-xr-x  3 vishal102  staff   96  6 Nov 13:46 mission-07-networking
drwxr-xr-x  3 vishal102  staff   96  6 Nov 13:46 mission-08-final-report
-rw-r--r--  1 vishal102  staff  948  6 Nov 14:04 README.md|
|Change directory(cd foldername)|it helps us to sitch between folders in the current-directory|cd mission-02-terminal|
|Create directory(mkdir)|it creates new folder in the current-directory|mkdir terminal-practice(creates a new folder named terminal-practice in the mission-02-terminal folder)|
|Create empty file(touch filename.txt)|it creates a new file inside my current folder|**touch notes.txt**-created a new file named notes.txt in my folder|
|Copy file(cp filename(path) destination(path))|it duplicates the file|a second file appears with same things with a new name|
|Move / rename file(mv file1 file2)|it renames or shifts the file|same file with a different name or same file in a different location,for eaxample:backup folder changed its name|
Display file contents (cat)|it shows the text stored inside a particular file|Printed the sentences I typed out|
