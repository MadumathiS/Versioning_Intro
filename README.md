# Introduction to Git and Github
Git and GitHub
Git is a Devops tool used for source code management. It is a free Version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development(work flows)
GitHub  is a provider of Internet hosting for software development and version control using Git. It offers the distributed version control and source code management functionality of Git, plus its own features.

# Installation
Before you start using Git, you have to make it available on your computer. Even if it’s already installed, it’s probably a good idea to update to the latest version. You can either install it as a package or via another installer, or download the source code and compile it yourself.

For download and installation go to the Git official website (https://git-scm.com)
For GitHub just create an account in the GitHub website (https://github.com)

# Configuration

# Git Settings
set a name that is identifiable for credit when review version history.
git config --global user.name "firstname lastname"
set an email address that will be associated with each history marker
git config --global user.email "youremail@example.com"
set a default editor (in my case I'm using vscode or code)
git config --global core.editor "code --wait"
set the default branch for all your repos
git config --global init.defaultbranch main

# GitHub Settings
To generate a new ssh key type the following command and complete:
ssh-keygen -t ed25519 -C "your-github-email@example"

 