# GIT HELP
## The most used commands ##

### INITIAL ###
#### Basic configuration ####
git config --global user.name "Roosterbear"
git config --global user.email "fernandoroosterbear@gmail.com"

### FIRST PROJECT ###
#### Create a repository ####
git init

#### Add to staged area [All files] ####
git add .

#### Commit changes [with a message] ####
git commit -m "First commit"



### MOVING ON GIT ###
#### What branch we are ####
git branch

#### View the log of commits ####
git log --pretty=oneline



### FIXING ERRORS ###
#### Backwards commit ####
git commit --amend

#### Delete a file in repository without deleting the local ####
git rm --cached file.txt

#### Delete a whole directory in repository without deleting the local ####
git rm --cached -r directory
