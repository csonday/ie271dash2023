# Guide to Git -- Part 2

This is a guide to using Git for collaborative programming. For more information on the technology behind Git, you can always visit [this documentation](https://git-scm.com/docs).


---

- [Guide to Git -- Part 2](#guide-to-git----part-2)
- [Preliminaries](#preliminaries)
- [Clone the Git](#clone-the-git)
- [Pushing and Pulling Changes](#pushing-and-pulling-changes)
  - [`git pull`](#git-pull)
  - [Uploading Changes into the Git](#uploading-changes-into-the-git)
- [DONE!](#done)


# Preliminaries
1. Create your account on GitHub.com.
2. Your Git should by accessible to you. Consult your groupmate who setup the Git repository via GitHub.
3. Install git on your PC/Mac. Find the appropriate installer [here](https://git-scm.com/downloads).


# Clone the Git
1. Cloning = copy the git on your local machine from the cloud
2. Open a terminal (can be in vscode). Point it to a directory where you want the cloned git will be. 
   
3. Go to your project's git repo page.
4. Proceed to the Code button and copy the HTTPS link

5. On the terminal, run the command `git clone <HTTP LINK HERE>`

# Pushing and Pulling Changes

## `git pull`
- Before coding anything, you want to update your copy of the codes.
- While inside the folder of your repo, run `git pull` to pull any changes uploaded by your peers.

## Uploading Changes into the Git
- To upload changes on the codes, you need to STAGE, COMMIT, then PUSH the changes. The following include the specific steps to updating the git from your PCs.

1. STAGE the changes
    - "Staging" is to group the changes to upload to the remote repo.
    - Do this by sending the command `git add .` on the terminal. The `.` means "all". You can cherry-pick files/folders you want to stage but this is rarely used.
    - You can also stage via VS Code. 

# DONE!

You are now able to share your code with your peers. With Git, you can also get back to previous versions of your codes, in case they stop working.

Generally, here is the cycle for the workflow: PULL -> CODE -> PUSH -> REPEAT.