# Guide to Git -- Part 1

This is a guide to using Git for collaborative programming. For more information on the technology behind Git, you can always visit [this documentation](https://git-scm.com/docs).


---

# Table of Contents
- [Guide to Git -- Part 1](#guide-to-git----part-1)
- [Table of Contents](#table-of-contents)
- [Git Setup](#git-setup)
  - [**STEP 1: INSTALL GIT**](#step-1-install-git)
  - [**STEP 2: CREATE A GIT via GITHUB**](#step-2-create-a-git-via-github)
  - [**STEP 3: ADD MEMBERS TO GIT**](#step-3-add-members-to-git)
- [Cloning A Git](#cloning-a-git)
- [Commits](#commits)
- [DONE!](#done)


# Git Setup
This section will be done by the group member responsible for the creation of the group's git. Other members will have to wait until the git has been setup.

## **STEP 1: INSTALL GIT**
- Find the appropriate installer [here](https://git-scm.com/downloads).

## **STEP 2: CREATE A GIT via GITHUB**
- Visit [GitHub.com](https://github.com/) to create an account
- Once you setup your account, you can find the following homepage.



- Create a new repository by clicking the appropriate button on the left sidepanel. You may follow my setup below

 - You will get the following window once you create the repository.

 ## **STEP 3: ADD MEMBERS TO GIT**
- On the same repository page, go to the Settings tab, then Collaborators option

- Proceed to adding your members. Tell them to create git accounts if you have to.
  

# Cloning A Git
- "Cloning" = syncing the repository from the cloud to your local machine (i.e. pc)
- Reference Instructions were taken [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository#cloning-an-empty-repository)
- I recommend the HTTPS cloning option
- Proceed to the Code tab


- Copy the HTTPS link provided
- Open a terminal. Ensure that you setup the directory to your preferred location where you want to put the git folder.


- From here, user the HTTPS link above to clone the repository.
  

- Checking my gitExamples folder, it now has an empty folder inside it. This is a copy of your online repository.

# Commits
- Copy your project files into your repo clone
    - *YOU MAY WANT TO LEAVE/EXCLUDE YOUR VENV FOLDER.* Generally, a venv should be personal/local to your computers.
- Upon copying, the files will not be synced to the cloud yet. You need to **commit** and **push** the changes.
- Before that, some notes!

1. Add the Repository into VS Code
    - On VSCode, you may add the folder you cloned from GitHub
2. The .gitignore file
    - create the .gitignore file as a plain text. You can include here files that you do not want to sync to the remote repository (i.e. the cloud).

3. STAGE the changes
    - "Staging" is to group the changes to upload to the remote repo.
    - Do this by sending the command `git add .` on the terminal. The `.` means "all". You can cherry-pick files/folders you want to stage but this is rarely used.
    

- You can also stage via VS Code. 


4. COMMIT the Changes
    - Once you've grouped the changes to upload, you COMMIT them so that you can add details about the changes.
    - In git, we track histories by looking at COMMITS. You can always go back to a commit if you want an older version of a file.
    - Here, we use the command `git commit -m '<description here>'`
    - You can also do it via VS Code


5. PUSH the Commits
    - "Pushing the commits" means sync the commits from your computer (i.e. local repo) to the cloud (i.e. remote repo).
    - do this with the command `git push`



# DONE!

You've now setup the repo! To verify, check your repository page on GitHub. 

Your groupmates may now clone the repo so they can push and pull updates.