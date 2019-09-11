# What is Git?
Git is a version control software

# What is github?
github stores users codes in the cloud and also allows multiple users to work on the same projects

# Main Git and github commands
| pwd | (tells users their location) |
| ls or ll | (shows users a short or long list of directory they can open) |
- ls -a ------------------(Shows hidden files)
- clear ------------------(clears all the lines)
- cd <directory name> ----(opens the directory)
- cd .. ------------------(goes back to previous level of file)
- mkdir <name> -----------(creates new directory)
- touch <name> -----------(creates new code file)
- rm <file name> ---------(removes code file)
- rm -rf <directory name> (removes directory)
- git init ---------------(initialises git)
- git add . --------------(adds a change in the working directory to the staging area)
- git commit -m 'name' ---(creates a new commit containing the latest code file)
- git status or ----------(shows the commit status of the code file)
- git log ----------------(shows a list of all committed code files)
- git remote -------------()
- git push <to> <from> ---(Pushes the master from local repo to github repo)

# .gitignore <file>
this is a command where the Git is explicitly told to ignore the chosen file. This ensures that chosen file is not pushed to github.
TO use this command:
- touch .gitignore
- open .gitignore in atom
- type in the files needed to be ignored
- in my case, I have added a file.txt
- Push the git to github
- wait for the magic to occur
