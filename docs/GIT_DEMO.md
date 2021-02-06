### Git and GitHub Quickstart
#### Overview
The main repository, or repo, is where our program lives. You copy (fork) this repo to make your own changes in branches, then send your changes back to be checked and added to the main repo. 
Main repository (upstream) < your fork (origin) < branches < commits

#### Configure Git settings
Git is for your local machine, GitHub is where we collaborate with pull requests and issue tracking.
>git config --global core.editor "vim"  (if you prefer Nano for a more informative writing environment, use "nano")
>git config --global user.name "Your Name"  
>git config --global user.email yourgmail@gmail.com  

#### Generate SSH keys
An SSH key provides security between your local machine and GitHub. 
>ssh-keygen -t ed25519 -C "yourgmail@gmail.com"

This generates a .pub file. Copy its contents to clipboard with the code below.
>clip < ~/.ssh/id_ed25519.pub

#### Add SSH key to your GitHub account
Navigate to SSH and GPG Keys in your GitHub personal settings.
Paste your SSH key into the box. You should now see it listed in SSH keys associated with your account.
Now you have a secure connection between your local machine and GitHub.

#### Clone your fork onto your machine 
This implicitly defines a remote named origin.
>git clone git@github.com:githubusername/agile_5e.git

#### Set up the upstream remote
This links origin with main on GitHub.
>git remote add upstream git@github.com:githubusername/agile_5e.git

#### Create a new branch
This creates a branch of your origin fork that you can edit locally. Branch early and often.
>git checkout -b my_git_demo

#### Create a new file
Touch creates a new, empty file.
Add adds any new files to the staging area (you are telling Git that you intend to commit the file you are adding).
>touch git_demo
>add git_demo

#### Create a commit
This adds your changes to your local repo.
>git commit

#### Add your work to the local repository
Before you add your work, check to make sure you have the latest changes from upstream. 
>git fetch upstream main (this will fetch upstream changes)  
>git rebase upstream/main (this will roll back your commit, apply the fetched changes, and then reapply your commit)

#### Push changes to your fork
This adds your local changes to your GitHub repository.
>git push origin my_git_demo

#### Create a pull request in GitHub
This proposes the addition of your changes to the main repository. The repo owner will double-check your work before adding it to main.
