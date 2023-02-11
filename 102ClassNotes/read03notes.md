# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Read 03: Revisions and the Cloud

[Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
- Through version control you can revert or project a previous version of a file. You can also modify and change them. (VCS)
- Centralized Version Control System (CVCS). Single server storing all the different changes and file versions that can be accessed by various people. This allows for more diverse collaboration and knowledge of who is doing what.
- Distributed Version Control System (DVCS).  Solution to the main problem with the CVS being a single point of failure.
DVCS allows for mirrored repositories to ensure there are backups if anything happens. This also allows for simultaneous workflows.
- Git is essentially a DVCS on steroids.  Helps track corrupted files, lost files, does snapshot saves.
![gitStageSteps](https://user-images.githubusercontent.com/109825175/211609192-05c8b981-62c5-4fa2-ac07-ee6945e23aa1.png)
- Large amount of steps that we did during installfest, good reference point if I ever need to redo this for any reason.
- We can import and clone using the terminal.
![lifeCycleFileStatus](https://user-images.githubusercontent.com/109825175/211610638-6a7313fd-ab18-4e75-bb94-1644c6dcf3a9.png)
- Can utilize git stash to store changes without committing to the file.  git stash apply can retrieve the hidden changes.
- Remote repositories can have set read/write or read-only privleges. This is where you can push information or pull data from.
- git remote command you can view origins of remote handles that you specify.
- get remote -v will show all the remote URLs next to the names.

## COMMAND TERMINAL CHEAT SHEET

- LAUNCHING A WEBPAGE FROM GITHUB, settings, pages, change branch from none to main and save. done.
- Only have to clone one time for each project from github to local computer.
- mv filename nameLocationFolder ex. mv random-web-idea courses
- git clone url, is how you clone a github respository to your current location in the terminal
- gitflow:acp / add, commit, push 
- git status , tell you what files have changed since your last commit
- git add filename, tell gits to includes changes in the next snapshot, stage files to have the snapshot prepared
- git add filename filename, can add multiple by adding each name with a space OR you can do  git add .   , this will grab all the changes on all the files.
- always check git status to ensure everything is staged properly.
- git commit -m "your message goes here"  (-m is a message flag so you can add a message)
- git push origin main  , commit takes the snapshot push sends to GitHub
- git pull origin main, if changes have been made on GitHub, you will be given options of what to do. Merge option may be best option FOR NOW.
- Vstudio will showcase the changes and YOU HAVE TO SELECT WHAT OPTIONS
- mkdir filename, creates a new directory or folder



## Things i want to know more about
- Need to play around in the terminal more to get comfortable with all of these new commands.
- Learning how to navigate more efficiently in repositories.
