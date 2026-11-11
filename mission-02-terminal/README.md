## 2.1 — Explore basic Terminal operation:
Operation/command used|What it does|What I Observed|
|:---|:---|:---|
|Current-directory display(PWD)|it shows us the path of the folder we are currently in|/Users/vishal102/desktop/digital-detective-8470|
|Directory listing(ls)|it lists downs all the folders and files of the current-working directory(doesn't show hidden files)|evidence			mission-01-computer-basics	mission-03-operating-system	mission-05-numbers-data		mission-07-networking		README.md
mission-00-setup		mission-02-terminal		mission-04-programs|
|Detailed listing(ls -l)|it shows all the files in the current-working directory with size and last updated date and the permisiion of files|drwxr-xr-x  2 vishal102  staff   64  6 Nov 14:25 evidence|
|Change directory(cd foldername)|it helps us to sitch between folders in the current-directory|cd mission-02-terminal|
|Create directory(mkdir)|it creates new folder in the current-directory|mkdir terminal-practice(creates a new folder named terminal-practice in the mission-02-terminal folder)|
|Create empty file(touch filename.txt)|it creates a new file inside my current folder|**touch notes.txt**-created a new file named notes.txt in my folder|
|Copy file(cp filename(path) destination(path))|it duplicates the file|a second file appears with same things with a new name|
|Move / rename file(mv file1 file2)|it renames or shifts the file|same file with a different name or same file in a different location,for eaxample:backup folder changed its name|
Display file contents (cat)|it shows the text stored inside a particular file|Printed the sentences I typed out|


### 2.2 — Safety Practice Questions
* **Difference between replacing and adding text:** Replacing (`>`) overwrites the whole file. Adding (`>>`) appends text to the end.
* **Difference between copying and moving:** Copying duplicates a file. Moving shifts the file or renames it.
* **Current-directory display:** Shows your exact path location map.
* **Directory listing utility:** Lists out available files at a glance.

## 2.3 - flags and pipes
* **flags comparision between ls and ls -lh**:
ls -lh makes the file sizes,permissions,and the last updated time date in a more human readable form than the ls and it also lists the hiddden files.
* **pipes explanation**-
pipe (|) takes output from the command on the left and gives it as an input to the command on the right-side.

## 2.4 Package Manager
* **version of homebrew**-Homebrew 7.0.11
*a package manager is like an app-store for packages where we update,download or remove them 
*it uses simple text commands instead of going into websites adn updating or removing or installing them.


## Evidence / files
* `terminal-practice/` sandbox folder.
* `mission-02-terminal/README.md`

## Commit details
* **Commit Message:** "Complete Terminal and file management mission"