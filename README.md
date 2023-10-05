# A02
# What is Github
# Github is a open source version control system which is a method for tracking changes to source codes or other documents. In addition to enabling collaborative editing, it also offers the option to go back to using a previous version in case new bugs are introduced. Some of its advantages include the ability to track source code changes, settle change **conflicts** between contributors, and interact with the command line version, which is known as Git. 
# How to set up Git/Github/Webstorm:
1. Install Webstorm using this link: https://www.jetbrains.com/student/
2. Install **Git** as a local program: https://git-scm.com/downloads
3. Create a **Github** account: https://github.com/join
4. Connect Github with Webstorm. To do so, go on Webstorm and press (Ctrl+Alt+S) to open up your system preferences. Then, select version control Git. Enter the path to the git.exe
5. Once again, open your system preferences in Webstorm, select appearance and behavior, then system settings, then passwords. Now, add your Github password to your Webstorm.
6. To create a **repository** from Github, click the "+" sign in the upper right corner and choose "create a new repository". Make the repository public and add the readme file
8. To create a repository from Webstorm, select your VCS and import into the Version Control
9. To **clone** the repository on WebStorm, go to VCS - Get from Version Control - Git. Then, paste the URL of the GitHub repository and choose a local directory where you want to clone it.
10. To create a **branch** on Webstorm, go to the bottom right corner and click "Git:**master**". Select a new branch, name it, then create.
11. To **Merge** branches on Github, go to your repository and click on the tab labeled "pull requests". Then select the branch you'd like to merge and create the pull request. You can also **Fetch** and Merge to get the latest changes to your repository. To do so, go to VCS - Git - Fetch. To then merge the changes, select VCS - Git - Merge changes
12. If there are **Merge Conflicts**, Git will let you know. You can open the file and manually fix the errors. Once the errors are resolved, add the files ('git add <filename>') and commit your changes.  
13. To import a repository from Github, go to the main page and select checkout from version control, enter your github repository name, and enter your local path name.
14. To create a webstorm file, choose file, then HTML, then HTML 5 or file, then stylesheet.
15. To add files to Git, open your Git dialog and click add. This adds to to a local file system. Be sure to **commit** your changes
16. To **push** change to **remote** repository, click "Ctrl - shift - K" OR "VCS - Git - Push". Your file should now be uploaded to Github
17. To setup Github pages and set up loaction, click settings and check your repository name. Then select "Master Branch" and note the published URL. 
18. Copy the Github.io URL into a browser and copy it into your moodle with your account URL.
    
# Glossary
- Branch: A synchronized version of a repository's code that enables concurrent work on various tasks by different contributors. Users establish branches in order to separate changes, create new features, address bugs, and then merge those changes back into the main code.
- Clone: a method of locating a remote repository so that users can edit local copies of the code.Cloning is often used to begin work on a project. 
- Commit: a record of repository modifications. Each commit includes a message outlining the changes as well as a special identifier.
- Fetch: downloads objects from another repository assuring that the local one is up to date. 
- Git: distributed version control system that permits users to track changes and code efficiently; a command line version of Github
- Github: open source version control system which is a method for tracking changes to source codes or other documents.
- Merge: the process in which you combine branches integrating separate lines of development
- Merge conflict: An error caused when Git is unable to merge changes from different branches to lines of codes. 
- Push: when local commits are sent to remote repositories, updating the remote with changes made to the local. 
- Pull: when changes from a remote repository are fetched and merged to a local repository, assuring that the local is up to date. 
- Remote: a repository that is separate from a user's local copy. It allows codes to be shared and worked on collaboratively. 
- Repository: location where a project's files, history, and configuration are stored and tracked

#References
canvas powerpoint 1: https://njit.instructure.com/courses/31572/files/5261437?module_item_id=1172885
canvas doc 2: https://njit.instructure.com/courses/31572/files/5261409?module_item_id=1172886
sources from google:
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line





