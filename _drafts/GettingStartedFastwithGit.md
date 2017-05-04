#Getting started fast with Git Part 

##Part 1 First Steps
You've got a Github account, you've configured git, now it's time to work quickly! 

1. Pull the repository from Github to your local machine. 


2. Now you've got the branch master! This is supposed to be clean - it's production. 


3. Create a Development Branch. This is your test environment. 


4. Oh crap, you've screwed up your local copy & want to overwite it with the server's copy. 

git fetch origin
git reset --hard origin/master


##Definitions

Git Clone
- Clone a repository into a new directory
- copies the repository and puts it in a folder of the same name

Git Pull
- Fetch from and integrate with another repository or a local branch

Git Merge
- Join two or more development histories together

Git Add
- put this file in our project

Git Add *

Git Add All

Git Status
- show the project status

Git Commit
- locking it into the repository
- not synced to the repository yet

##How it works. 

workflow ------------------------------->

Local Directory | Index | Head | Remote Directory

code starts here ----->	 &  ----->	ends here. 

The folder on your computer (local directory) and folder on the server (remote directory) both have a copy of the master and development branches. 

You can create the local directory first or the remote directory first. 



##Definitions

Git Add
- Add file contents to the index

Git Commit

Git Push

##Resources

###Git - the simple guide by Roger Dudler
http://rogerdudler.github.io/git-guide/

###Git-scm
git-scm.com

###Github Basics for Mac or Windows & Source Control Basics
https://www.youtube.com/watch?v=0fKg7e37bQE


Github the readme file is the instructions you are gonna give to people who use the repo
It's automatically displayed when you open the repository. 

Add commits all throughout the day. 

