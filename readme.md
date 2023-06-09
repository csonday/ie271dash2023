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
![image](https://github.com/csonday/ie271dash2023/assets/55682386/d1959f3e-922d-416b-a14d-fd77836e8254)

3. Go to your project's git repo page.
4. Proceed to the Code button and copy the HTTPS link
![image](https://github.com/csonday/ie271dash2023/assets/55682386/6b4eaec1-1006-42e0-afd6-aa174ce442bd)

5. On the terminal, run the command `git clone <HTTP LINK HERE>`
![image](https://github.com/csonday/ie271dash2023/assets/55682386/6c69a30d-cc8e-4347-ba2b-0556d1226fcf)

After cloning your git, you should see the files in your preferred folder. 
![image](https://github.com/csonday/ie271dash2023/assets/55682386/c3472006-9528-4be0-8a26-1b9efdb97529)

# Pushing and Pulling Changes

## `git pull`
- Before coding anything, you want to update your copy of the codes.
- While inside the folder of your repo, run `git pull` to pull any changes uploaded by your peers.
![image](https://github.com/csonday/ie271dash2023/assets/55682386/ff411d7f-bee5-41ef-aebb-8cb522424e28)

## Uploading Changes into the Git
- To upload changes on the codes, you need to STAGE, COMMIT, then PUSH the changes. The following include the specific steps to updating the git from your PCs.

1. STAGE the changes
    - "Staging" is to group the changes to upload to the remote repo.
    - Do this by sending the command `git add .` on the terminal. The `.` means "all". You can cherry-pick files/folders you want to stage but this is rarely used.
![image](https://github.com/csonday/ie271dash2023/assets/55682386/b08b62be-ac97-4f6a-8bcf-27282cc68a78)

    - You can also stage via VS Code. 
![image](https://github.com/csonday/ie271dash2023/assets/55682386/48c96afa-5037-4955-8dee-598ad77f910c)

2. COMMIT the Changes
    - Once you've grouped the changes to upload, you COMMIT them so that you can add details about the changes.
    - In git, we track histories by looking at COMMITS. You can always go back to a commit if you want an older version of a file.
    - Here, we use the command `git commit -m '<description here>'`
    - You can also do it via VS Code

![image](https://github.com/csonday/ie271dash2023/assets/55682386/69b414e5-657a-443a-a3e6-1b47038341b8)


3. PUSH the Commits
    - "Pushing the commits" means sync the commits from your computer (i.e. local repo) to the cloud (i.e. remote repo).
    - do this with the command `git push`
![image](https://github.com/csonday/ie271dash2023/assets/55682386/a9807dd0-347e-4662-b390-3e6d236273b3)

# DONE!

You are now able to share your code with your peers. With Git, you can also get back to previous versions of your codes, in case they stop working.

Generally, here is the cycle for the workflow: PULL -> CODE -> PUSH -> REPEAT.
