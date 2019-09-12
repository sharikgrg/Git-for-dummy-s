# What is git?
git is a version control software

# What is github?
github stores users codes in the cloud and also allows multiple users to work on the same projects

# Main git and github commands
| git commands    | uses     |
| :------------- | :------------- |
| pwd       |  tells users their location  
| ls or ll  | shows users a short or long list of directory they can open
| clear     | clears all the lines
| cd <directory name> | opens the directory
| cd .. | goes back to previous level of file
| mkdir <name> | creates new directory
| touch <name> | creates new code file
| rm <file name> | removes code file
| rm -rf <directory name> | removes directory
| git init | initialises git
| git add . | adds a change in the working directory to the staging area
| git commit -m 'name' | creates a new commit containing the latest code file
| git status or | shows the commit status of the code file
| git log | shows a list of all committed code files
| git remote | manages list of remote entries
| git push <to> <from> | Pushes the master from local repo to github repo

# .gitignore <file>
This is a command where the git is explicitly told to ignore the chosen file. This ensures that the chosen file is not pushed to github.
To use this command:
- on gitbash do touch .gitignore
- open .gitignore in atom
- type in the files needed to be ignored
- in my case, I have added a file.txt
- Push the git to github
- wait for the magic to occur
