# aa2986-A02

Part 1: Step-by-Step Tutorial on Using Git, GitHub, and VS Code
Step 1: Install Git
Git is the distributed version control system that you'll need to manage source code and collaborate with others.
Download the Git installer for your operating system from the official Git website:
https://git-scm.com/downloads

Step 2: Install VS Code
VS Code is a powerful and lightweight code editor that supports Git integration.
Download it here:
https://code.visualstudio.com/Download

Step 3: Install Git Extension for VS Code
Once you have VS Code installed, install the official Git extension by following these steps:
Open VS Code.
Click on the Extensions view icon on the Sidebar.
Search for "Git" in the Extensions Marketplace.
Install the official Git extension.
Once installed, configure Git with your username and email:

Step 4: Connect Git to VS Code
After installing Git and VS Code, follow these steps to connect the two:
Open VS Code.
Open a folder where your project is stored (or create a new one) by navigating to File > Open Folder.
Open the integrated terminal in VS Code (Ctrl + `) or go to Terminal > New Terminal.
In the terminal, run:

Step 5: Create a GitHub Account and Repository
GitHub is a web-based platform for hosting Git repositories.
If you don’t have a GitHub account, sign up at: https://github.com/join
Once logged in, create a new repository by clicking the New button at the top of the dashboard.
Follow the instructions to name and set up your repository.

Step 6: Connect GitHub Repository to VS Code
In VS Code, use the terminal to clone the GitHub repository to your local machine:
git clone https://github.com/your-username/your-repo.git
Open the cloned repository in VS Code.

Step 7: Make Your First Commit
Make changes to a file or create a new file in the repository.


Step 8: Push Changes to GitHub
After committing your changes, push them to the GitHub remote repository

Step 9: Fetch, Pull, and Merge
To fetch the latest changes from the remote repository without merging them:

Step 10: Branching and Merging
To create a new branch for developing a feature:

git checkout -b feature-branch
Make changes, commit, and push the changes to the new branch.
When ready, merge the changes back into the main branch:

________________________________________________________________________________________________________________________________________

PART 2: Glossary of Git Terms
Branch: A copy of the code that diverges from the main line of development, allowing changes to be made without affecting the main project.

Clone: A copy of a repository that is downloaded from a remote repository like GitHub to your local machine.

Commit: A snapshot of changes in the repository's history, including a message explaining the changes.

Fetch: A command used to download updates from a remote repository without merging them into the local branch.

Git: A distributed version control system used to track changes in source code.

GitHub: A web-based platform that hosts Git repositories and facilitates collaboration between developers.

Merge: The process of combining changes from different branches into one branch.

Merge Conflict: When Git is unable to automatically resolve differences between branches during a merge and requires manual intervention.

Push: Sending committed changes from your local repository to a remote repository like GitHub.

Pull: A command that retrieves updates from the remote repository and integrates them into the local branch.

Remote: A version of a repository stored on a different server, such as GitHub, that can be connected to for collaboration.

Repository: A directory or storage space where your project's files and the history of changes are stored.
