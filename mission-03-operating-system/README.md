## Task-
Understanding how an OS works,differences between paths,exploring file permissions.
 
## 3.1 Exploring Our Operating System
|Information explored|what it tells us|observation|
| :--- | :--- | :---
|Operating system|it tells us about the version of the OS|
ProductVersion:		27.2|
|Current account identity|it tells us the name of the user whose currently logged in|abc345 <--(name of the user).|
|Available and used storage|it shows us how much storage is left in the Hard-Drive|/devs/disk3s1s2   460Gi    13Gi   348Gi     4%    487k  3.7G    0%|
|System activity snapshot|it shows the active memory usage and CPU usage|i saw some list of the systems and tools running|

## 3.2 Understanding Processes
**What is a Process**-Basically,a process is a program that is being executed on a computer at the moment.
**What does PID column represent**-A PID is process ID its a unique identication number given by a computer to a program that is currently being executed to keep a track of it.Example:-(25384 ttys001    0:01.99 -zsh)

**Give two examples of processes that may be running on your computer**- current process running on my computer **Google Chrome** and **VScode**

## 3.3 learning the differences between Actual Path and Relative Path
**Actual Path**:it shows the complete path right from the star that is the root,For example:(/Users/abc345/desktop/digital-detective-8470)
**Relative Path**:it shows the path of the file or the folder from the current directory,for example:(digital-detective-8470/evidence)
**Owner permissions:**when i ran ls -l it showed me the permision where owner had rwsx so owner had permission to read ,write and execute the folder as well example:(drwxr-xr-x  2 abc345 staff   64  6 Nov 14:25 evidence)

## 3.4 Understanding responsibilities of  an OS
| OS responsibility | Your explanation in simple words | Simple Example |
| :--- | :--- | :--- |
| **Process management** |it Controls how a programs opens, runs, and closes down without any crash. |for example: Closing a stuck application using Force Quit. |
| **Memory management** |it takes Decision and  Decides which running app will get to use the computer's RAM. | Allocating extra RAM when opening a heavy browser tab. |
| **Device management** |This helps the computer to talk to external parts(hardware) plugged into it. | Connecting a wireless mouse or plugging in a charger. |
| **File management** |It Organizes how files are named, saved, moved, and stored in folders. | Creating a new folder inside your Documents directory. |
| **User interface / shell** |it is what a user sees,that is,giving the user a visual or text display to click or type commands. | Using the Finder desktop interface or typing inside Terminal. |
| **Security and permissions**| Stops unauthorized users from messing with or deleting system files. | Prompting for a password before installing a new app. |

**Difficulties faced and understandings**
getting through the commands which help in knowing about OS was a bit challengiong and also finding pid was also a bit challenging ,other than that it was a pretty good learning.