## How to set up git repo (LOCALLY)

- Create a new folder for my git project
- cd into the folder ( this moves you into the correct folder in terminal)
- Run the command:  `git init`
- Now your web project is a git repository.

## Make some changes to your web project

eg. add an index.html, css file, javascript file etc.

## Do your first commit

A commit  is like a snapshot of your site. You keep making these as your project develops.

To make a commit you first add your changes to the staging area.

To do this with: ` git add . `

Now commit  the changes with ` git commit -m "<type your commit message here>" `

## Repeat. Change some files,  git add, then git commit

To check previous commits: `git log`

## To create new branch:

`git checkout -b branchname`  then make some changes and git add, commit again.

And go back to your master branch with: `git checkout master`
