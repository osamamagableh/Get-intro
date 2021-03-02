# Git

### what is a Git ?


**Git** is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it . Git do io local domin and Files in Git can reside in three main states: committed, modified and staged 

now let us know what these states

1. **committed** : Data is securely stored in a local database
2. **modified** : File has been changed but not committed to the database
3. **stages** : lagged a file’s changed version to be committed in the next snapshot

**the figure bellow shows these stages**
![stages](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

to use Git you must download it before in your computer

let us know how to download it 

- **Mac**

The simplest method for installing Git on a Mac (for Mavericks 10.9 and above) is running Git from the Terminal. If Git is not installed, you will see a prompt for installation.

- **Ubuntu**

You can try installing Git via your distribution’s inherent package management tool.

$ sudo apt-get install git

- **Windows**

You can download Git by visiting this link and following the posted directions:

http://git-scm.com/download/win

## Setting up a Git Repository

- **Importing**

To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

1. Switch to the target project’s directory

2. Use the git init command :

**$ git init**

3. To start tracking these repository files, perform an initial commit by typing the following:

**$ git add *.c**

**$ git add LICENSE**

**$ git commit -m “any message here”**

- **Cloning**

You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

**$ git clone https://github.com/test**

By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

To clone a repository into a directory with another name of your choosing, use the following command format:

**$ git clone https://github.com/test mydirectory**



