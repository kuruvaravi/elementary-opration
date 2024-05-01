

1.	installing the GIT 
	Download Git: Go to https://git-scm.com/download/win and get the Git installer for Windows.
	Run Installer: Double-click the downloaded file to start the installation process.
	Follow Instructions: The installer will guide you through the process with simple prompts. Just click "Next" or "Install" as appropriate.
	Choose Options: During installation, select "Use Git from the Windows Command Prompt" so you can run Git commands from the Command Prompt or PowerShell easily.
	Finish Installation: Once the installation completes, click "Finish".
	Check Installation: Open Command Prompt or Git Bash and type git --version to make sure Git is installed correctly. You should see the installed version displayed.

2.	manage public and private repository
	Create a Repository: If you haven't already, create a repository on GitHub. Sign in to your GitHub account, click on the "+" icon in the top right corner, and choose "New repository". Fill in the necessary details like repository name, description, etc., and click "Create repository".
	Access Repository Settings: Once your repository is created, navigate to its main page. You'll see options like "Code", "Issues", "Pull requests", etc. Click on the "Settings" tab located near the top-right corner of the repository page.
	Change Repository Visibility: In the Settings page, scroll down until you find the "Danger Zone" section.
	Under "Danger Zone", you'll find the "Change repository visibility" option.
	Click on "Change repository visibility" and select "Private" from the dropdown menu.
	Confirm Changes: After selecting "Private", GitHub will prompt you to confirm the change. You might need to provide your GitHub password or re-enter your account credentials to confirm the action.
	Save Changes: Once confirmed, click on the "Make private" button to save your changes.
	Verify Repository Status: After making the repository private, its visibility will be updated accordingly. You'll notice a lock icon next to the repository name, indicating that it's now private.


3.3.	Write and execute the commands to set up and configure git on your local machine.
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/162d741e-2c6e-475c-88c5-7dc8e5f920ba)
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/b1ebb356-4ebe-4648-83ab-6daabc482b44)
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/fadada7c-fb3d-4992-ad9c-317a6455871f)


4.44.	performing basic operations in Git. 
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/afacc426-5fbd-47f4-9197-64542f09b798)
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/aaf3e793-7146-4084-aaee-2ec781868d65)


5.5.	Write and execute the three important steps of version control. 
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/4ff377e4-ab70-4426-86a7-d1c47a22228d)
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/01812074-d3f6-4bf3-90bf-8464aafbe1fd)
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/423d1848-8c2d-441b-a203-3f2bc5a0c9b8)



6.6
6.	execute git add, git commit, git push, git pull, git status.
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/dea0d73d-ff8e-4a2e-8478-bfa190b5b215)
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/63fe80ff-d54d-4f86-8cf5-f436d77aefb2)
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/59391045-ad99-4a72-b693-7eb6b8e28b26)
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/c4127195-d068-4370-85a5-1576916e9d32)
![image](https://github.com/kuruvaravi/elementary-opration/assets/153703114/0147bb25-157c-4b47-879b-989700ab4bed)


7.77.	Explain and execute how to create branches and merging branches. 

Creating branches

To keep track of changes to this file using git, you need to:
1.	Clone the repository.
2.	Move into the cloned repository
3.	Create a new branch using the command (replace feature-branch with your desired branch name).
git checkout -b feature-branch
4.	Make modifications to files in your project.
5.	Use git add to add the changes to the staging area
6.	Commit the changes with a meaningful message

Merging branches
To keep track of changes to this file using git, you need to:
1.	Switch back to the main branch.
git checkout main
2.	Merge the branch into the main branch
git merge feature-branch
3.	Resolve conflicts (if necessary)
i.	Open the conflicting files and resolve the conflicts manually.
ii.	After resolving conflicts, add the changes to the staging area and commit:
git add .
git commit -m "Merge feature-branch into main"
4.	Push changes to github using the following command.
git push origin main


.8.88.Create and Address GitHub Issues.
	Create a new issue in your repository:
i.	Go to your GitHub repository.
ii.	Click on the "Issues" tab.
iii.	Click the "New issue" button.
iv.	Fill in the issue title and description.
v.	Optionally, assign the issue to a collaborator, apply labels, and set milestones.
2.	Assign the issue to a collaborator:
i.	Within the issue, use the "Assignees" section to assign the issue to a collaborator.
ii.	The assigned collaborator will receive notifications about the issue.
3.	Label the issue with appropriate tags:
i.	Apply labels to categorize and prioritize issues.
ii.	Create and use labels like "bug," "feature," or any relevant labels for your project.
iii.	Labels can be added when creating the issue or edited later.
4.	Close the issue using a commit message:
i.	Make changes to the codebase to address the issue.
ii.	In your local repository, commit the changes with a commit message that references the issue number:
git commit -m "Fix #1: Resolve issue with feature X"
Replace "1" with the actual issue number.
iii.	Push the changes to GitHub:
git push origin main
The issue will be automatically closed when the commit is pushed.


viva .

1.	What is git’s feature?
Git features version control, branching and merging, distributed development, collaboration tools like pull requests, and cryptographic integrity checks.

2.	What are the advantages of using git?
Git provides version control, enables collaboration, supports branching and merging, ensures code integrity, and is highly flexible and widely supported.

3.	What are git’s limitation?
Learning Curve
Large File Handling
Merge Conflicts
Lack of GUI for Some Operations
Risk of Data Loss

4.	What are branches, and what command creates a new branch?

Branches in Git are parallel lines of development that diverge from the main line (usually called the "master" or "main" branch) to work on different features, fixes, or experiments independently. They allow developers to isolate their work from the main codebase until it's ready to be merged.
The command git branch <branch_name> creates a new branch in Git.

5.	What is git merge?
git merge is a command used to integrate changes from one branch into another branch. When you merge one branch (called the source branch) into another branch (called the destination branch), Git combines the changes made in the source branch with the changes in the destination branch.

6.	When should you use git push and git pull? 
You should use git push when you want to send your local commits to a remote repository, typically after making changes and committing them locally. This action updates the remote repository with your changes.
On the other hand, you should use git pull when you want to retrieve changes from a remote repository and integrate them into your local repository. This is typically done to update your local repository with changes made by others in the remote repository.

7.	Is Github an Open-Source Software?
GitHub itself is not open-source software, but it hosts millions of open-source projects. The platform provides proprietary services for managing Git repositories, issue tracking, project management, and collaboration tools. However, many of the projects hosted on GitHub are open source, meaning their source code is freely available for anyone to view, modify, and distribute according to the terms of an open-source license.

8.	What Is Repo?
"Repo" is short for "repository." In the context of Git and GitHub, a repository is a storage space where your project's files and revision history are stored. It contains all the files for your project, along with a history of each file's changes. Repositories can be either local (stored on your computer) or remote (stored on a server, like GitHub).

9.	What is GitHub fork?
Forking on GitHub refers to creating a personal copy of someone else's repository. When you fork a repository, GitHub creates a copy of the original repository in your GitHub account. You can then freely experiment with changes in your fork without affecting the original project. Forking is commonly used to propose changes to someone else's project (via pull requests), to experiment with changes, or to create your own version of an existing project.

10.	Can we change our GitHub username?
Yes, you can change your GitHub username.

11.	Is it possible in git to merge a branch into the master? 
yes, it is possible in Git to merge a branch into the master branch.

12.	What language is used in git?
Git itself is primarily written in the C programming language. However, Git also includes scripts and tools written in various languages, including shell scripting (Bash), Perl, Tcl, and Python. These scripts and tools contribute to Git's functionality and support its operation across different platforms and environments.

13.	What is the significance of Git version control?
Git version control allows tracking changes, enabling collaboration, managing code history, facilitating branching and merging, ensuring code integrity, and streamlining deployment.

14.	List the Types of version control system.
Centralized Version Control Systems (CVCS): In CVCS, there is a central server that stores the repository, and developers check out and commit changes directly to this central repository. Examples include CVS (Concurrent Versions System) and SVN (Subversion).
Distributed Version Control Systems (DVCS): In DVCS, each developer has their own local copy of the repository, including the full history of the project. Developers can work independently and synchronize their changes with remote repositories as needed. Git is the most popular example of a DVCS.

15.	Can we delete the github account. 
Yes, you can delete a GitHub account. 

16.	Name any two git repository hosting services that are common. 
Two common Git repository hosting services are Bitbucket and GitLab.

17.	What is git clone?
git clone is a Git command used to create a copy of a repository from a remote source, such as GitHub, Bitbucket, or GitLab, to your local machine. It copies all the files, commit history, and branches from the remote repository to your local machine, allowing you to work on the project locally and synchronize changes with the remote repository.


18.	What is staging environment?
A staging environment is a pre-production environment that closely resembles the production environment. It serves as an intermediate step between development and production environments, allowing developers to test their code in a controlled environment before deploying it to production.

19.	What is github issues?
GitHub Issues is a feature provided by GitHub for tracking tasks, enhancements, bugs, or any other topics related to a repository. It allows users to create, assign, and track issues within a project. Each issue can have a title, description, labels, assignees, milestones, and comments.

20.	What is a git submodules and git aliases?
Git submodules and Git aliases are two different features of Git:
Git Submodules: Git submodules allow you to include a separate Git repository as a subdirectory within your own repository. This is useful when you want to include another project as a dependency in your own project. Git submodules allow you to track the specific version of the dependent repository that your project relies on, making it easier to manage dependencies and collaborate with others.
Git Aliases: Git aliases are custom shortcuts or abbreviations for Git commands. They allow you to create shorter, more memorable names for frequently used Git commands or command sequences. For example, you could create an alias co for git checkout, ci for git commit, or st for git status. Git aliases can be defined either globally (for all repositories on your system) or locally (for a specific repository) in your Git configuration file. They help improve productivity and streamline your workflow by reducing the need to type out long Git commands repeatedly.

























