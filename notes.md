#Intro to Github:
Great video by Kat: https://www.youtube.com/watch?time_continue=42&v=0WomDVxONf4&feature=emb_logo

VCS - Distributed Version Control System (VCS):
    - A central hub that stores code in a repository (repo)
    - Can give you off network access
    - More security concerns can arise
    - Allows multiple people to work at the same time
    - More collaboration

Git Flow: (Stage, Commit, and Push)
    - changes to a file have to be STAGED
    - Git is a tracking system. It watches files we tell it to watch, and it's going to track changes on those files

    To start Git tracking a file, we have to start staging it
    1) TO STAGE A FILE: (tracking changes, not saving) - whenever you make changes to a file you have to stage those changes in order to then save them
        [ git add notes.md ]
        shortcut: [ git add . ] (be careful in the real world tho)

    2) TO SAVE A FILE:
        [ git commit -m "Adds notes." ] (you have to add a message to any commit decribing what the change DOES) (Use commit often!)

    - command save allows the terminal to realize that you have code that has been modified and should be saved

    3) SAVE TO REMOTE REPO (GITHUB) (it's been local on your computer up to this point) (origin is the remote repo and is just the conventional naming method) (master relates to the master branch, the branch we are pushing to in this case)
        [ git push origin master ]

    *) Discover what remote repos are connected to your local repo (can be multiple)
        [ git remote -v ]

    *) TO CHECK THE STATUS OF A FILE: (if return is green: GOOD. if return is red: git commit)
        [ git status ]

Questions:
1- Do you have to git add before every git commit? 
2- Do you have to git push after every git commit?
3- What are flags?
4- Someone mentioned yesterday that employers look at your github account. Why?