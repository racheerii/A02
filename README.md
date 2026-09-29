# A02
## How to Use GitHub and VS Code Together:

Before doing anything, make sure you have VS Code and Git downloaded, as well as a GitHub account.

Go to github.com, and log into your account. Create a repository named "A02", and make sure that under *Configuration* you select "Add README".

Then, open VS Code and hit Ctrl+Shift+P. Type in "git clone" and select "Git: Clone". Next, click "Clone from GitHub" and "Allow". This will bring you to your browser and ask for you to log into GitHub. When you are done, go back to VS Code.

In the search bar, it should say "Repository name (type to search)". Enter the name of the repository you want to use, in this case it should be your "[user.name]/A02". Then, select a folder where you would like to clone the repository. Once, it finishes loading, open that folder.

Before editing your repository, you must set up your Git username and email. Click the "..." in top left of VS Code and open a new terminal. In the terminal, open up Command Prompt and enter these commands:
git config --global user.name "XYZ"
git config --global user.email "XYZ@example.com"

Once you enter these commands, you can now start editing your repository! Go back to the Explorer by hitting Ctrl+Shift+E, and click the README.md file. This is where you will do the assignment for A02.

After making your changes to the README.md file, hit Ctrl+S, and open the Source Control by hitting Ctrl+Shift+G. Click the down arrow next to the blue Commit button, and click "Commit & Push". Click "Yes", and it will then ask you to enter a commit message. Click Commit again, and Save. When you check your repository on github.com, you will see the changes you have just made. You are now using VS Code and GitHub together!

## Glossary:

**Branch** – A parallel version of a repository; It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.

**Clone** – A copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy; When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.

**Commit** – An individual change to a file (or set of files); Commits usually contain a commit message which is a brief description of what changes were made

**Fetch** – Adding changes from the remote repository to your local working branch without committing them; Unlike git pull, fetching allows you to review changes before committing them to your local branch.

**GIT** – An open source program for tracking changes in text files; Written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.

**Github** – A web-based platform that stores Git repositories in the cloud, allowing developers to work together on projects. It helps manage code changes and supports both public and private repositories. GitHub is widely used for version control and collaboration in software development.

**Merge** – Takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line.

**Merge Conflict** – A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

**Push** – To send your committed changes to a remote repository on GitHub.com.

**Pull** – When you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date.

**Remote** – The version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.

**Repository** – The most basic element of GitHub. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.

## References:

https://youtu.be/V7WpadAi3RI?si=jsrJneiGt1idOYye

https://utrechtuniversity.github.io/workshop-computational-reproducibility/chapters/readme-files.html

https://docs.github.com/en/get-started/learning-about-github/github-glossary#github-app