# Learning Git

## What is Git?  

![confused](https://i.imgur.com/ls1Oh6n.png)

_**Snapshots**_   
Git is a DVCS that stores data in a file system made up of snapshots. 
Each time you save a changed version of your project — called commit — 
Git creates a snapshot of the file and stores a reference to it. If 
the file has not changed, Git only stores a reference to the already
-stored identical version of it.

_**Local Operations**_  
Git mostly relies on local operations because most necessary information 
can be found in local resources. This allows for process expediency because 
a project’s history resides on the local disk, eliminating the need to 
fetch history information from the server, and allowing one to continue 
work on a project even when not online or on a VPN.

_**Tracking Changes**_  
Every single change applied to any file or directory is tracked by Git. 
And, as the gatekeeper, Git will always detect file corruption or loss 
of information in transit.

_**Loss of Data**_  
Git is set up to greatly minimize the possibility of irreversible damage 
to files, such as accidentally lost data. Git makes it extremely difficult 
for a snapshot of your file that is committed to be lost.


_**States**_  
Files in Git can reside in three main states: committed, modified and staged.

_**Committed**_  
Data is securely stored in a local database.

_**Modified**_  
File has been changed but not committed to the database.

_**Staged**_  
Flagged a file’s changed version to be committed in the next snapshot.

![flow chart](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png
)

**Setting up a Git Repository**

_**Importing**_  
To import an existing project or directory into Git, follow these steps using 
the Terminal or Command Line:
Switch to the target project’s directory
Example:
$ cd test (cd = change directory)
Use the git init command
$ git init
Note: At this stage, you have created a new subdirectory named .git that has 
the repository files. Tracking has not commenced.

To start tracking these repository files, perform an initial commit by typing the following:
* $ git add *.c
* $ git add LICENSE
* $ git commit -m “any message here”  
Now, your files are tracked and there’s an initial commit. We will discuss the particular commands in detail soon.

**Cloning**  
You can also create a copy of an existing Git repository from a particular server 
by using the clone command with a repository’s URL:

* $ git clone https://github.com/test  
By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

**Check File Status**  

To determine the state of files, utilize the git status command:
* $ git status  

**Tracking and Staging a New File**  
Single File
Track one file only by using the following format:  

* git add filename

**Committing a File**  

After staging one or multiple files, you should commit the changes and record what you did within the commit message:

* $ git commit -m “made change x,y,z”

* Committing All Changes  
* $ git commit -a

**Pushing Changes**  

Next, you would push changes to a remote repository. We will discuss remote 
repositories in more depth in the next section. For now, we will look at a general 
overview of pushing changes to remotes.  

_**Example:**_  
  * $ git push origin master
