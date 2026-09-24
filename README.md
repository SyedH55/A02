# A02

PART 1: Directions

Setting up Git

Setting up Git is as simple as going to the Git install page at https://git-scm.com/install/, choosing your operating system, and then installing the corresponding setup file. Now using a coding platform of your choice (VS code is what this will be based on), install the Git Bash extension. From there, in your terminal you want to set your username and email. Your username can be whatever you desire as Git runs locally, but your email has to be the same as the one you use for GitHub as this as how they link. In order to set your username, use the git config --global user.name "[enter your name]" command in the terminal. Then to enter your email, use the git config --global user.email "[enter your email]" command. Your Git is now fully set up.

Setting up GitHub

Go to GitHub.com and create an account using the same email you set up Git with. From there, enter your username and password and create your account. From there, install GitHub Desktop at https://github.com/apps/desktop and then Authorize Desktop in order to easily sync up your local Git account with GitHub's cloud servers. Now you can create a repository in GitHub (either on the website or app) by clicking the new repository button in the repositories tab. Give it a name and add a ReadMe file and then click create repository at the bottom. Now that you are in your new repository, you can connect it to your coding software of choice by clicking the green code button. Next, copy the HTTPS clone link and navigate to your terminal. Using the Git Bash extension we can write the command git clone [enter HTTPS link] and click enter. You will be prompted to select a folder to keep this repository in locally on your computer. Select or create a folder of your choice and you are done, your GitHub is fully setup and connected to VS code (or other coding environment of your choice).

Setting up WebStorm

Start by going to the WebStorm website at https://www.jetbrains.com/webstorm/ and download the setup file. Open up the app and go through with the setup process. This includes customizations and IDE preferences. From there, go to projects from the side bar and either clone your GitHub repository (same as before) or create a new project. From there you are good to go and start coding.

PART 2: Defintions

Branch: A copy of your stable main files in which you can test out new code without worrying about losing progress or accidentally breaking your main project. Allows for safe experimentation of new ideas.

Clone: A clone is full, local copy of a repository and all its files on your computer. This includes files, branches, and version history. Can also be used to connect a repository to an IDE.

Commit: A commit is a save point that saves all the changes you've made while also time-stamping it. Every commit is saved, meaning that you can go back at any point and track the history of a project over time. It also records exactly what changes were made and by who.

Fetch: Used to download all new commits, files, and references without changing any of the actual code or files. Makes it easier to see if any new changes have been made and what those new changes are.

GIT: Git is a local version control system that is used to track changes in code and manage files during the development process.

GitHub: GitHub is an online platform where code can be stored, shared, collaborated on, and tracked.

Merge: Merge takes changes from one code branch and integrates them into another branch, implementing all of the changes and testing that was done in the branch.

Merge Conflict: A merge conflict occurs when Git is unable to automatically combine code changes from different branches. This happens when conflicting changes happen on the same line or when certain files are deleted. This requires human intervention to choose which files/code to keep and which to discard.

Push: Push is a command where you upload all the code you did on your computed to a repository on GitHub.

Pull: The pull command updates your computer with what is in the repository.

Remote: A remote points to a copy of your repository that is hosted on the internet.

Repository: A repository is a project folder that stores all of a project's files, documentation, and all the history of every change made to the code within the files.

References:

https://docs.github.com/en/get-started/git-basics/set-up-git

https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account

https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html

https://docs.github.com/en/pull-requests/reference/branches

https://github.com/git-guides/git-clone

https://docs.github.com/en/pull-requests/reference/commits

https://graphite.com/guides/github-pull-vs-fetch

https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F

https://www.coursera.org/articles/what-is-github

https://www.w3schools.com/git/git_branch_merge.asp?remote=github

https://www.geeksforgeeks.org/git/merge-conflicts-and-how-to-handle-them/

https://www.geeksforgeeks.org/git/what-is-git-pull/

https://docs.github.com/en/get-started/git-basics/about-remote-repositories

https://github.com/orgs/community/discussions/181855