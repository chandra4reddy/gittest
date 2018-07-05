# Git Training
* git will store files in repository and it has four area of memory areas
   #STASH(temporary storeage area)  #WORKING AREA(current working area)  #INDEX(place files before commit)  #REPOSITORY(has all history)
                                     add                                  commit                             checkout
                                     remove
                                     mv
#Working Area:
#tree ----- shows tree view

#Repository:
.git has git info
Object has the info and db
each commit is a snapshots in repository
head :current pointing commit
branch:

#Index:
index is unique to git
git diff will compare index data and working area data
git diff --cached will compare stage file and repository file
#WorkFlow:
*edit file stage file commit file 
edit use vim filename --- add data
git status 
git add filename
git status
git diff
git diff --cached
git commit -m "description"

*repository to working area
git checkout branch : copies data to index and working area
git rm filename : removing file from index area
git mv newfilename old filename : will rename
git diff branch1 branch2


# git log --graph --decorate --online

# git show xxxx

# git show branchname

# git show HEAD

#git show ^HEAD

#git show HEAD~2

# git blame filename

#git diff HEAD HEAD-2

# git diff branch1 branch2

# git log --patch gives u actual changes

git log --grep apples --online

git-grep

git log -3 --online



























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

