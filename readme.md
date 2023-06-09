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
![image](https://github.com/csonday/ie271dash2023/assets/55682386/8530b8d3-089f-4eaa-8098-24a68984fd36)

- Create a new repository by clicking the appropriate button on the left sidepanel. You may follow my setup below
![image](https://github.com/csonday/ie271dash2023/assets/55682386/a2b40973-9eb6-4fb1-9da4-4aa6117e8b96)

 - You will get the following window once you create the repository.
![image](https://github.com/csonday/ie271dash2023/assets/55682386/d3c64c93-fa5a-4927-b898-719c376fed21)

 ## **STEP 3: ADD MEMBERS TO GIT**
- On the same repository page, go to the Settings tab, then Collaborators option
![image](https://github.com/csonday/ie271dash2023/assets/55682386/b7b90d76-7887-46ad-b7d4-b38b4e638892)

- Proceed to adding your members. Tell them to create git accounts if you have to.
  

# Cloning A Git
- "Cloning" = syncing the repository from the cloud to your local machine (i.e. pc)
- Reference Instructions were taken [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository#cloning-an-empty-repository)
- I recommend the HTTPS cloning option
- Proceed to the Code tab
![image](https://github.com/csonday/ie271dash2023/assets/55682386/c06d0293-77ef-44b6-9ddf-03a32d2a0f48)


- Copy the HTTPS link provided
- Open a terminal. Ensure that you setup the directory to your preferred location where you want to put the git folder.
![image](https://github.com/csonday/ie271dash2023/assets/55682386/6928beb0-8f84-4258-a465-a4fc267f43fb)


- From here, user the HTTPS link above to clone the repository.
![image](https://github.com/csonday/ie271dash2023/assets/55682386/dfc58856-58ee-453a-888c-f7a0b1d97ee2)

- Checking my gitExamples folder, it now has an empty folder inside it. This is a copy of your online repository.
![image](https://github.com/csonday/ie271dash2023/assets/55682386/704c37ec-bd54-43bb-bd13-1c0a6673cfe3)

# Commits
- Copy your project files into your repo clone
    - *YOU MAY WANT TO LEAVE/EXCLUDE YOUR VENV FOLDER.* Generally, a venv should be personal/local to your computers.
- Upon copying, the files will not be synced to the cloud yet. You need to **commit** and **push** the changes.
- Before that, some notes!

1. Add the Repository into VS Code
    - On VSCode, you may add the folder you cloned from GitHub
2. The .gitignore file
    - create the .gitignore file as a plain text. You can include here files that you do not want to sync to the remote repository (i.e. the cloud).
![image](https://github.com/csonday/ie271dash2023/assets/55682386/8c98bb61-8871-4e69-a3d2-deb1706b4338)


3. STAGE the changes
    - "Staging" is to group the changes to upload to the remote repo.
    - Do this by sending the command `git add .` on the terminal. The `.` means "all". You can cherry-pick files/folders you want to stage but this is rarely used.
![image](https://github.com/csonday/ie271dash2023/assets/55682386/c82d5cc8-6ce0-4097-b802-71333e94ed68)


- You can also stage via VS Code. 
![image](https://github.com/csonday/ie271dash2023/assets/55682386/59e565f7-3d58-4c6d-835f-f4a3e9d693a4)


4. COMMIT the Changes
    - Once you've grouped the changes to upload, you COMMIT them so that you can add details about the changes.
    - In git, we track histories by looking at COMMITS. You can always go back to a commit if you want an older version of a file.
    - Here, we use the command `git commit -m '<description here>'`
    - You can also do it via VS Code
![image](https://github.com/csonday/ie271dash2023/assets/55682386/51a663d7-7542-4510-9e29-47be93f5632a)



5. PUSH the Commits
    - "Pushing the commits" means sync the commits from your computer (i.e. local repo) to the cloud (i.e. remote repo).
    - do this with the command `git push`
![image](https://github.com/csonday/ie271dash2023/assets/55682386/043b7261-588c-48e6-8448-78c83e2b5e29)



# DONE!

You've now setup the repo! To verify, check your repository page on GitHub. 

Your groupmates may now clone the repo so they can push and pull updates.
