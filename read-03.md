[Back to Home](README.md)

# Read 03

## Version Control

Version Control records the changes that developers make on their code as versions so they can access it again later instead of keeping all the changes on one last updated files. This feature helps developers to get back to their previos work whenever they need to instead of losing deleting all the new changes that were added and modify the code again. It also allows developers to compare changes betweem versions.

Version control started as a local version control system that each developer has it on his own machine, but the collaboration between developers created the need of a centralized versrion control to make things easier for the team to access the same files and docunments. Since centralized control versioning is vulnerable as a single point of failure, the need to create a distributed version control arised. DVCS allows users to create mirrored repositories as a backup.



## What is GIT

Git is a distributed version control system that saves files as snapshots. Eveytime the user makes a change to his file and commits this change, GIT saves this change as a snapshot and does no change to the original file which means that two different versions of the same file exist at that moment.

The image below shows how GIT works

![GIT](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)



## GIT Cheatsheet

The table below shows some of GIT commands and how to use them:

| Command | Usage of the command |
|---|---|
| `code .` | This command opens VS Code |
| `git clone "link" `| Clone a repository to your local machine from github |
| `git config --global user.name "Name Name"` | Configures the settings of git by adding your username |
| `git config --global user.email "emal@email.com" ` | Configures the settings of git by adding your email |
| `git config --list` | Displays the saved configuration if git |
| `git command --help` | Shows help to the user ragarding the specified command |
| `git status` | Shows the user which branch hes on and states if there is any changes were applied on the any of the files in the repository |
| `git add *` | changed files are tracked and staged for committing |
| `git commit -m “made change x,y,z”` | commit changes and record what you did within the commit message |
| `git push origin master` | pushes changes from the local “master” branch to the remote repository named “origin” |

[Back to Home](README.md)