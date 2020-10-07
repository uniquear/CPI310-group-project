# CPI310-group-project

https://docs.google.com/document/d/1etDs4tIElUIzxwet0LrGoH6E9ybtG_5rL3gchDinm8I/edit?usp=sharing


# TL;DR

Start on `master`
```
git checkout master
git pull
```
checkout a new branch
```
git checkout -b myCoolNewBranch
```
Make some cool new stuff in the project, and then push it
```
git add -A
git commit -m "I did a thing!"
git push
```
then create a pull request on GitHub, wait for review, and merge!

## How Do I Use Git?
The easiest way to manage your git commands is through the terminal! I would **strongly** recommend dowloading [CMDR](https://cmder.net/) (Use "Download Full"). All you need to do is unzip it into a folder in your User directory. It's free and lightweight and it allows you to use Unix style commands instead of Windows commands. It also comes with git pre-installed. If you already have a terminal setup you're happy with, great! But this tutorial will us Unix terminal commands, so be ready! (Serously, CMDR is awesome)
**Here's a git cheat sheet! More explanation below**
```
git fetch                       // gets info from the main repository, you can use it to check for changes
git status                      // check the status of your current changes, see if you're up to date
git pull                        // update your local repo with the latest on the main repo (will not overwrite your work!)
git checkout -b myNewBranch     // creates a new branch and checks it out simultaneously!
git add -A                      // add all changes to the stage
git add filename.etc            // add a specific file only, to the stage
git commit -m "my message"      // simultaneously commit and add a commit message
git push                        // pushes your commit to the main repo
git checkout master             // switch back to the master branch 
y**If you get stuck** and you just want to delete it all and start over you can use `git reset --hard` and that will revert you to the last commit and delete **all** of your changes since the last commit **without any confirmation** so use it wisely. Seriously, be careful with this command! (but don't worry, anthing commited is safe)


## Step 1: Cloning the repo!
It's pretty simple! Just create a folder somewhere in your user directory (or wherever you want to keep the project) and then in the terminal, navigate to that folder. Once you're in the folder that you want to clone to repo into, type the following command
```
git clone https://github.com/uniquear/CPI310-group-project.git
```
You will the be prompted to enter your GitHub username and password 

**A quick note about navigation using terminal commands**
Unfamiliar with terminal? Let's say you have the folder `C:\Users\MyName\cpi310project` and you want to put the project there. 
In your terminal, the command `cd` or "change directory" is how you move from folder to folder. 

If you're in the `Users` directory and you want to move into a folder `C:\Users\MyName\cpi310project`, type:
```
cd MyName           // it would be your user name
cd cpi310project
```
If you need to move back out of a folder, use
```
cd ../
```
If you need to see all the stuff in the current folder, type
```
ls
```

