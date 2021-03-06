# GIT HELP
## The most used commands ##

#
> INITIAL (Just the first time configuration)

#### Basic configuration ####
```git
git config --global user.name "Roosterbear"

git config --global user.email "fernandoroosterbear@gmail.com"
```

#
> FIRST PROJECT 

#### Create a repository ####
```git
git init
```
#### Add to staged area [All files] ####
```git
git add .
```
#### Commit changes [with a message] ####
```git
git commit -m "First commit"
```
#### Now create a GitHub proyect

#### Get a project ####
```git
git remote add origin https://github.com/Roosterbear/your-proyect.git
(git branch -M main) <-Optional
```
#### You can use Visual Studio Code to push easily 
or...
```git
git push -u origin main
```

#
> MOVING ON GIT

#### What branch we are ####
```git
git branch
```

#### Change branch ####
```git
git checkout coworker
```
#### Deleting a branch ####
```git
git branch -d coworker
```
#### View the log of commits ####
```git
git log --pretty=oneline
```

#
> FIXING ERRORS

#### Backwards commit ####
```git
git commit --amend
```
#### Delete a file in repository without deleting the local ####
```git
git rm --cached file.txt
```
#### Delete a whole directory in repository without deleting the local ####
```git
git rm --cached -r directory
```


~~Finished~~

* Fooling with tables ;)

| 1 | 2 |
| -: | -: |
| 3 | 4 |
