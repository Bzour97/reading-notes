# Summarize

You need to communicate with remote repositories, versions of a project that is online or on a network to cooperate with Git projects. You can operate with many repositories, for which read/write or read-only capabilities are available. Remote repositories can be used by teams to push data and pull to and from.

## push
We use the git push format to push your changes "upstream" to share, as follows:
git push [remote-name] [branch-name]

### Example:

$ git push origin master

This command pushes committed changes from the local "master" branch to the "origin" server.
But, if you write to the server from which you copied, and if someone else has not pushed the modifications you have not yet tested, we can only successfully push the changes. If an employee pushes up the modifications after the clone, the push doesn't function. We'll have to pull the new modifications and merge them with our branch till you get the changes properly. 

## The Git: 

Git is a DVCS which saves data in a snapshot file system. Git provides an instant view of the file and keeps a reference to it every time the updated version of your project is saved — called commit. If the file has not changed, Git saves simply the same version of the file that has already been saved.

## Cloning
You can also build a copy of an existing Git repository using a clone command with the URL of a repository from a certain servers:

$ git clone https://github.com/test

You have copied all files for a project by cloning the file. This command creates a directory named "test" that has an initialized.git directory that has copies of all versions of all files for the project being provided. A copy of the latest version of the project is also automatically checked — or found for editing.

## Now I would to talk about Version Control:

Version Control is a system that allows you to track change between various versions of a file or a collection of files. You may restore a prior version of a file or project, track and compare changes, and go back to the previous version. File errors may be easily fixed using a version control system (VCS).

### Types of Version Control: 
1. Distributed Version Control
2. Local Version Control
3. Centralized Version Control

## For more informations : [Click Here](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7)

