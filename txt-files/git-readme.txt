https://github-enterprise-11-10.irl.hp.com/hp/training_repo.git


angadic@ANGADIC1 /c/Sites/training_repo (master)
$ cat README.md
training_repo
=============

Mission: Add your name and a short message to the UpdateMe file

Steps:
### 1. Fork this repo on GitHub
   - click the fork button: (this will give you your own personal copy of the repo under your username on GitHub, like https://github-enterprise-11-10.irl.hp
m/your-user-name/training_repo) ![Clone Fork](screenshots/fork.png)

### 2. Clone this repo to your computer
   - Copy the Git Clone URL from your fork:  ![clone_screenshot](screenshots/clone_fork_url.png?raw=true)
   - Open [Git Bash shell](http://git-scm.com/downloads) and run ```git clone YOURCOPIED_GIT_CLONE_URL```.  This should copy the repo down to your local dev


### 3. Make a topic branch on the repo:
   - In Git Bash shell, run ```git branch whatever_you_want_to_name_your_branch```.  Run ```git status``` to verify that you have a new topic branch, but you
 still on the master (default) branch: ![Git Status](screenshots/git_branch_status.png)

### 4. Switch to your topic branch
   - ```git checkout whatever_you_want_to_name_your_branch```

### 5. Verify that you're on your topic branch:
   - ```git branch``` ![Git Branch](screenshots/git_branch_2.png)

### 6. Verify that you don't have any changes
   - ```git status```

### 7. Add your name to a file or something.
   - Make sure the file shows as modified by running ```git status```

### 8. Stage your change to be added
   - ```git add whatever_file_you_want_to_be modified```  verify with ```git status```

### 9. Commit your file
   - ```git commit -m "my commit message"```.  Verify file as been committed with ```git status```

### 10. Push your Branch up to github
   - ```git push origin whatever_you_want_to_name_your_branch```

### 11. Open a Pull Request against the fork in GitHub
   - Navigate to your fork on GitHub, like https://github-enterprise-11-10.irl.hp.com/your-user-name/training_repo
   - Click on the green Compare & pull request button: ![open pr](screenshots/open_pr.png)
   - Alternatively switch to your branch on GitHub and click on pull request: ![open pr 2](screenshots/open_pr_2.png)

### 12. Create the Pull Request
   - Click on the Create pull request button: ![create pr](screenshots/create_pr.png)

### 12. Edit & Merge Pull Request
   - Add a comment and Mention someone by entering @ and select a name. An email will be sent to that person to review and merge your changes.
   - Go to the main project, like https://github-enterprise-11-10.irl.hp.com/hp/training_repo, and click the Pull Request icon on the sidebar: ![pull request
creenshots/repo-tabs-pull-requests.png)
   - Open the Pull Request and click on the green Merge pull request button.
   - You can merge your branch yourself by clicking on the Merge pull request button. NOTE: This is not the correct procedure when collaborating on a project
[pr comment](screenshots/pr_comment.png)

### 13. Delete Branch
   - Once your branch has been merged successfully you can go ahead and delete your topic branch: ![delete branch](screenshots/delete_branch.png)

Thats it!!  You have now successfully collaborated on a project.  Feel free to make any other changes and create new branches and pull requests.

angadic@ANGADIC1 /c/Sites/training_repo (master)
$
