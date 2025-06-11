# list of linux commands
- ls - list directory contents
- cd - change directory
- pwd - print working directory
- cp - copy files and directory
  # Diff b/w git pull and git fetch
  git pull | git fetch
  ---------|-----------
  download the changes and keeps merges to local repository | downloads the changes and keeps in remote repo
  # Diff b/w git merge and git rebase
  git merge | git rebase
  ----------|-----------
  used to bring the changes from feature branch to main branch | used to commit the changes from feature branch on top of the latest main branch

  - https://github.com/manuyu4407/practice_git/new/main/git.txt
  - Setting up
# Assuming your project is in a folder named "Project" on your Desktop.
Starting from scratch
cd ~/Desktop/Project
git init
git checkout -b develop
touch README.md
Open the README.md file you just created in your text editor. Describe your project. I've provided a basic template below for what it's worth. Save it.

# Go to Github (or Bitbucket or whereever you want to save your code in the cloud). Create a new project.

If you're on Github, do not check Initialize this project with a README since you just made one.
Determine your SSH clone url. On Github it's probably something like git@github.com:USERNAME/PROJECT.git. Should be on the project's page somewhere.

Add your remote.

  - git remote add origin {{the link you just copied}}
