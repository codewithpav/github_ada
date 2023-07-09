# github_ada

## Overview

Today we will cover the following:

- overview of version control

- use cases

a) local project on your machine that you want to track changes.
b) remote project to collaborate on.

the flow: working directory --> 2. staged files --> 3. .git directory  (repository) 

- set up and configure git on your machine
- initialise a project on your machine
- first commit

Remote repository

- make a branch
- merge a branch
- create a collaborative environment

by the end of this session, you should have a high-level understanding of using git locally, the basic commands of 

## Set up Git

Check it is installed on the machine, by opening the terminal and inserting git --version

Check if your config values are set by inserting git --config. This is important to track code changes when collaborating with other developers. 

If not, git config --global user.name "XYZ" and git config --global user.email "xye@dsa.com"

## Initilialise a project on your machine

ls into directory and insert git init 

check to see if .git repository has been set up ls -la

advance - git ignore file that specifies the files you want to ignore.

## First commit

Create a file

git status

git add -A adds everything to the staging area

Add file to the staging area

git status

to commit:

git commit -m "message here"

git status

git log will show you hash numbers, shows that every committed change is tracked, and can therefore rolled back if required.

make a change to the file

git status

## Make a branch

git checkout -b issue1

make a change to the text file

git status

git commit -m "Error fixed"

git checkout -b issue1

git merge issue1. 


