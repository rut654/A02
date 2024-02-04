# A02

**How to setup Github:**
<br>

GitHub is a website used to track changes in source codes and host your repositories online.  
1.	Visit the Github website at **https://github.com**. If you have an account, click sign in  or click sign up  to create an account.

2.	Open terminal on Linux/MacOS or command prompt on Windows. Set your GitHub username and email using **git config --global user.name "Your Name"**
**git config --global user.email “your.email@example.com”**
3.	You can clone the repo by **git clone https://github.com/your_username/your_repo.git**
On GitHub, you can go to your profile, and click on the second tab repositories.  
4.	Then on the far right click on the green button that says new for creating a new repository. 

5.	Name your repository. It is optional if you want to give a description of what is in your repository. 
6.	Select whether you want your repository to be public or private 
7.	You can add a README file to better explain about your repository or your purpose. 
8.	Once done click **Create repository**.

**How to setup Git:**
<br>
Git is a free open-source version control system that allows to create projects and teams to collaborate with each other. Programmers can make iterative changes to their code and trace back changes they saved.   
1.	Download Git from the website **https://git-scm.com/downloads**and select the OS you are using. 
2.	Follow the prompt for the installation instructions.
3.	Open terminal on linux/macOS or command prompt on Windows. 
4.	Set your username and email address by the following:
**git config --global user.name "Your Name"**
**git config --global user.email “your.email@example.com”**
5.	If you already have a git repository, then you can clone the repository by the command **git clone https://github.com/your_username/your_repo.git**
If you don’t have a git repository, then you can create one by using git init or if you have created a GitHub account, then you can go to your profile, and click on the second tab repositories.  
6.	Then on the far right click on the green button that says new for creating a new repository. 
7.	Name your repository. It is optional if you want to give a description of what is in your repository. 
8.	Select whether you want your repository to be public or private. 
9.	You can add a README file to better explain about your repository or your purpose. 
10.	Once done click Create repository. 
11.	Create a filename using git add filename or to save all changes use git add.
12.	Then to update your changes, create a commit message using git commit -m "Your commit message"
13.	To create a new branch to trace back your code incase of bug issues, use git branch branch_name
14.	Then to switch to that branch use git checkout branch_name
15.	If you want to switch to your main branch, use git checkout main
16.	If you want to update your changes to GitHub, do git push origin main or git push origin branch_name.
17.	If you run into any conflict, then you have to manually resolve the conflict and then merge the changes.

**General GIT commands:**
<br>
1. **git init**: Initializes a new Git repository in the current directory.
2. **git clone [url]**: Clones an existing Git repository from a remote server to your local machine.
3. **git add [file]**: Adds a file or changes to the staging area, preparing them to be committed.
4. **git commit -m "[commit message]"**: Commits the changes in the staging area to the local repository with a descriptive commit message.
5. **git status**: Displays the status of the working directory, showing which files are modified, staged, or untracked.
6. **git push**: Pushes committed changes from your local repository to a remote repository.
7. **git pull**: Fetches changes from a remote repository and merges them into the local branch.
8. **git branch**: Lists all local branches in the repository.
9. **git checkout [branch name]**: Switches to the specified branch.
10. **git merge [branch name]**: Merges changes from the specified branch into the current branch.
11. **git remote**: Lists the remote repositories associated with the local repository.
12. **git log**: Displays a history of commits in the repository.
13. **git diff**: Shows the differences between changes in the working directory, staging area, and the last commit.
14. **git reset [file]**: Removes a file from the staging area, preserving its changes in the working directory.
15. **git stash**: Temporarily shelves changes in the working directory, allowing you to switch branches or perform other tasks.

**How to setup VSCODE:**
<br>
Visual Studio Code (VSCode) is a lightweight, open-source source code editor developed by Microsoft.
1.	Download VSCode: Go to the Visual Studio Code website and download the installer for your operating system (Windows, macOS, or Linux) at https://code.visualstudio.com/.
2.	Install VSCode: Once the installer is downloaded, run it and follow the on-screen instructions to install VSCode on your system.
3.	Launch VSCode: After installation, launch VSCode from your application menu or by double-clicking the VSCode icon on your desktop. 
4.	Extensions: VSCode supports extensions that enhance its functionality for various programming languages, frameworks, and tools. To install extensions, click on the Extensions view icon on the Sidebar, then search for the extensions you want to install. 
5.	Integrating with Git: Git can be integrated with VSCode. Install Git on your system and then configure VSCode to use Git. VSCode provides Git integration allowing you to perform common Git operations like commit, push, pull, and merge directly from the editor.

**GLOSSARY:**
<br>
1. **Branch** - When you create a new branch, you create a new pointer to the current commit. Branches allow developers to work on different features or bug fixes independently without affecting the main codebase. Once changes in a branch are complete, they can be merged back into the main branch.
2. **Clone**- Cloning a repository in Git means creating a copy of an existing Git repository on your local machine. This allows you to work on the project locally and make changes. Once done it can be merged into the original repository.
3. **Commit**- When you commit changes in Git, those changes get saved to the repository's history. A commit in Git is a snapshot of changes made to the repository at a particular point in time.
4. **Fetch**- Retrieves the latest changes from a remote repository (such as GitHub, GitLab) to your local repository. However, fetching doesn't automatically merge these changes into your local branch. Fetching updates your remote-tracking branches so you can see what other developers have been working on.
5. **GIT**- A free open-source distributed version control system. It is used for tracking changes in source code during software development. It allows multiple developers to work on the same project concurrently and merge their changes seamlessly.
6. **Github**- GitHub is a web-based platform built on top of Git. It provides hosting for software development projects, version control and collaboration tools. GitHub is used for open-source projects as well as private repositories. Repositories can be hosted online.


**References**:
<br>
1. Microsoft (Ed.). (2021, November 3). Visual studio code - code editing. redefined. RSS. https://code.visualstudio.com/ 
2.	GitHub (2019) GitHub Guides Tutorial. Retrieved  March 19, 2019, from
 https://guides.github.com/activities/hello-world/
3.	Beer, B. (2018). Introducing GitHub. 2ed. O’Reilly Press.
4.	Git. (n.d.). https://git-scm.com/ 

