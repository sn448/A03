GitHub Tutorial

Definitions:

Git: an open source program that is the core technology used in GitHub. It is used in software development and can track source code changes. 

Github: a system built to host Git repositories and projects

Repository: where all the files for a particular project are stored

Clone: a copy of a repository stored locally on a computer, rather than online. Chnages made on the local version of a clone can be pushed to the remote (online) version to keep both versions in sync when online.

Commit: a record of the changes made to the file. when a revision is made, it must be committed with a commit message for Git to keep track of what was changed. 

Push: sends changes from a local file to a remote repository, like one located on GitHub

Pull: brings in changes from remote repositories to a local file and merges them

Branch: a parallel version of a repository. Changes made here will not affect the main repository branch. Once completed, this branch can be merged with the main branch and published.

Merge: takes changes from one branch and incorporates them into another. 

Merge conflict: occurs when Git is unable to automatically resolve differences between two codes.

Fetch: brings in new remote changes from an online source without merging them into a local file. This allows you to compare changes in the new remote file with the local one.

Remote: the version of a file that is hosted on a server like GitHub.

TUTORIAL

Creating a new project on webstorm:
1. Install Web Storm and Git, and create a GitHub account.
2. Once webstorm is installed, go to settings (Ctrl+Alt+S) and choose Version Control then Git. 
3. Choose the location and test to make sure Git and Webstorm are connected by clicking Test.
4. Click New Project on the WebStorm main page. Choose a location and name the project.
5. Create a new html file within that project and name it. 
6. Begin working on the project.

Uploading a project to a repository on GitHub:
1. In webstorm, click VCS→ import to version control→ create Git Repository.
2. Commit the changes (VCS→ Git→ commit).
3. A dialog box will open, where you can enter your Github username and password. Click Set and commit.
4. Share the project on github (VCS→ import to version control→ share project on github). 

Synchronizing Github and computer files:
1. Once you have made changes to the local file, you can merge it with the remote file by committing the change (VCS→ Git→ commit) then pushing to github (VSC→ git→ push)
2. When you add to the github repository, you can merge with the local one through a pull request, or when you try to push a commit from a local to the remote repository, a dialog box will open and ask you to merge. 

References:
1. https://help.github.com/en/github/getting-started-with-github/github-glossary
2. "Additional Instructions on Creating a Git and Github repository." by Dr. Art Hendela
