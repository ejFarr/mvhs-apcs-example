# Git

## One Time Setup

`git config --global user.name "Evan Farr"`
`git config --global user.email "roboproductions200@gmail.com"`

## Project Setup

`git init`
`touch .gitignore`
add `*.class` to .gitignore file and save it.
`git add .`
`git commit -m "Initial commit"`

## 3 Step Repeating Commit Proccess
1. Make changes to code
2. Stage related changes
    * git add
3. commit changes wth a message
    *git commit -m "message"

## Commands

* status  -> tell me what files have been staged or commited
* add -> add file to stage
* rm --cached -> remove file from stage
* git commit -> a "present tense description of what changed"
* log -> show history of commits, enter to move down a page
* checkout --file -> discard changes if not on stage

## Problems
* commit without -m -> esc : wq
* wrong message -> git commit --amend -m "new message"
* wrong commit -> git checkout COMMMIT_ID