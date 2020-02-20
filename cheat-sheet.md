# Cheat Sheet

*Intro:*  
* Linux has a graphical user interface and it works pretty much like the GUI's on other systems that you are familiar with such as Windows and OSX.   
* The command line can be interesting and can be intimidating.   
* A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.  
* A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.
* If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.  
* If on Linux then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'.  
* If you are on Windows and intend to remotely log into another machine then you will need an SSH client. A rather good one is Putty (free) .  
* Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell.   


*Commands*  
1. cd - change directory
2. ~ brings back to home (begining)
3. cd .. back/ up a directory
4. pwd - lists where you are
5. git init -  to create a Git repository
6. git add <your-file-name>
7. add git commit -m "message"
8. git status - gives current status of local repo
9. git push origin master - makes local changes reflect on github
10. git commit - saves changes 
11. git fetch - looks for changes on GitHub
12. git pull - combo of fetch and save chanages
13. git diff origin/master - will show changes and compare from Github and your local machine but not commit anything.
14. code . - opening all files
15. GIT HUB - KEY
16. git clone https://url-to-clone  

*Paths*  
 * Whenever we refer to either a file or directory on the command line, we are in fact referring to a path. ie. A path is a means to get to a particular file or directory on the system.

*Absolute and Relative Paths*  
* There are 2 types of paths we can use, absolute and relative. Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path (either way, the system will still be directed to the same location).
* To begin with, we have to understand that the file system under Linux is a hierarchical structure. At the very top of the structure is what's called the root directory. It is denoted by a single slash ( / ). It has subdirectories, they have subdirectories and so on. Files may reside in any of these directories.  
* Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )  
* Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.  
