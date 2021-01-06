# General idea
main repository (upstream) < your fork (origin) < branches < commits

# Configure Git Settings
git config --global core.editor "vim"  
git config --global user.name "Your Name"  
git config --global user.email yourgmail@gmail.com  

# Set Up GitHub
## generate ssh keys
ssh-keygen -t ed25519 -C "yourgmail@gmail.com"

## add ssh public ssh key to your github account

## fork the main repository

# Do Stuff on Your Machine!

## clone your fork onto your machine (this implicitly defines a remote named origin)
git clone git@github.com:hirja/agile_5e.git

## set up the upstream remote
git remote add upstream git@github.com:MAustin428/agile_5e.git

## create a new branch
git checkout -b jake_git_demo

## edit something
touch git_demo
add git_demo

## create a commit
git commit

# Add Your Work to the Main Repository

## check to make sure you have the latest changes
git fetch upstream main (this will fetch upstream changes)
git rebase upstream/main (this will fetch upstream changes, including your own)

## push changes to your fork
git push origin jake_git_demo

## create a pull request to add your changes to the main repository (this will allow the repo owner to double-check your work before adding it to main)