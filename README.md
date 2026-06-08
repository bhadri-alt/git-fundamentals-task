# Git Fundamentals Task



## Introduction



This repository was created as part of the Git Fundamentals learning program. The objective of this task is to gain practical knowledge of version control using Git and collaborative development using GitHub. Git is one of the most widely used version control systems and is an essential tool for software developers.



\---



## Objectives



* &#x20;Understand the purpose of Version Control Systems (VCS)
* &#x20;Learn the basics of Git and GitHub
* &#x20;Create and manage local repositories
* &#x20;Track file changes using Git
* &#x20;Commit project updates with meaningful messages
* &#x20;Work with branches and merging concepts
* &#x20;Connect local repositories to remote repositories
* &#x20;Push and pull changes from GitHub
* &#x20;Understand collaborative development workflows



\---



## Prerequisites



Before starting this task, the following were installed and configured:



* &#x20;Git
* &#x20;GitHub Account
* &#x20;Git Bash / Command Prompt
* &#x20;Internet Connection



\---



## Topics Covered



### &#x20;1. Version Control Systems



* What is Version Control?
* Benefits of Version Control
* Centralized vs Distributed Version Control



### 2\. Git Basics



* Installing Git
* Configuring Git
* Understanding Repositories



### 3\. Repository Management



* Creating Local Repositories
* Cloning Existing Repositories
* Initializing Repositories



### 4\. File Tracking



Staging Files

Viewing Repository Status

Tracking Modifications



### 5\. Commits



* Creating Commits
* Commit Messages Best Practices
* Viewing Commit History



### 6\. Branching



* Creating Branches
* Switching Branches
* Merging Branches



### 7\. Remote Repositories



* Connecting to GitHub
* Pushing Changes
* Pulling Updates
* Synchronizing Repositories



### 8\. Collaboration Concepts



* Forking Repositories
* Pull Requests
* Code Reviews
* Conflict Resolution



\---



## Git Commands Practiced



### Configuration



git config --global user.name "Nallamothu Bhadri"

git config --global user.email "your-email@example.com"

git config --list



### Repository Creation



mkdir git-fundamentals-task

cd git-fundamentals-task

git init



### File Operations



git status

git add README.md

git add .

git rm filename



### Commit Operations



git commit -m "Initial commit"

git commit -m "Updated README file"

git log

git log --oneline



### Branch Operations



bash

git branch

git branch feature-branch

git checkout feature-branch

git checkout main

git merge feature-branch



### Remote Repository Operations



git remote add origin https://github.com/username/git-fundamentals-task.git

git remote -v

git push -u origin main

git pull origin main

git clone <repository-url>



### Useful Commands



git diff

git stash

git restore filename

git reset --soft HEAD\~1





## Workflow Followed



1\. Installed Git on the local machine.

2\. Configured Git username and email.

3\. Created a local repository using `git init`.

4\. Added project files to the staging area.

5\. Committed the files to the repository.

6\. Created a GitHub repository.

7\. Connected the local repository to GitHub.

8\. Pushed the project to the remote repository.

9\. Verified successful synchronization between local and remote repositories.



\---



## Challenges Faced



Understanding the difference between staging and committing.

Learning how local and remote repositories interact.

Configuring GitHub authentication.

Remembering commonly used Git commands.

Understanding branching and merging concepts.



\---

## Learning Outcomes/



After completing this task, I am able to:



Create and manage Git repositories.

Track and monitor file changes.

Create meaningful commits.

Work with branches.

Push and pull code from GitHub.

Understand collaborative development workflows.

Use Git confidently for project version control.



\---



## Conclusion



This task provided practical experience with Git and GitHub. The knowledge gained will help in future software development projects by enabling efficient version control, collaboration, and project management.



\---



## Author



Name   : Nallamothu Veera Bhadra Chowdary

Program: Full Stack Web Development Internship

Task   : Git Fundamentals

Year   : 2026



