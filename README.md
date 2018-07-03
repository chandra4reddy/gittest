# gittest
Git config set properties:
# git config --global user.name "Hemachandra"
# git config --global user.email "Hemachandra.reddy@gmail.com"
list of git configs
# git config -l
Git password cache on that machine
# git config --global credential.helper wincred
Default text editor for git was VI we have some many text editors
we can chagnge default text editor for git by using below command
# git config --global core.editor "atom --wait"
before using this we need to install atom editor

show tree info of git repo
# tree .git
Create repository
# git init myproject
myproject is new repository name
Cloning
# git clone <repo URL>
git history log as graph
# git log --oneline --graph
git configs we can do in three levels
@1 System --- Usually in /etc or similar

@2 Global --- ~/.gitconfig

@3 Local --- .git/config
edit this file
# git config -e
Creating alias names
# git config --global alias.lga 'log --graph --oneline --decorate --all'

list of alias name in config and we can edit as well
# git config -e --global 
Git status
# git status

adding file
# git add <filename>

#git commit

