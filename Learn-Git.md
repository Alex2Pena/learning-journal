## Git 
- is a DVCS - Development control system
- lets multiple developers work on same code
- view, apply, and remove changes
- keeps all project files in a single repository

## Comits
- are similar to the Save as function.
- keeps track of changes as diffent versions of same filename.
- keeps track of what the file looked like at different points
- each commit can have a **HEAD** meaning "You are here"
- each commit can have a messages "caption" with reason for changes made

## GitHub 
- remote cloud based - like a social media for code
- uses Git on local machine to upload local code to <GitHub>
- different languages should be stored in different repositories
  
## Clone a repo on GitHub with terminal to local machine
- open terminal and verify you are at root level
- create new directory **mkdir ________**
- navigate to directory **cd _________**
- create new directory within **mkdir_______**
- navigate to directory **cd ________**
- goto repo on github and hit clone then copy url
- in terminal type **git clone *URL*** hit enter
- in terminal type **git remote -v** to verify
- in terminal type **git status** to verify if you have the current version

## Open repo in VS code with terminal
- type **code .** to launch VS code with current repo
- make changes in vs code if needed
- type **git add** or **git commit-a** to update file with changes
- type **git reset** to unstage or undo changes
- type **git commit -m "reason for change"** to add message to commit change
- type **git push origin master** to upload/publish to github
- type **git fetch** to compare origin/master file if changes have been made on github
- type **git pull origin/master** to download changes made on GitHub to local file.
- 

