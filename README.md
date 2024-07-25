# PLpBasicGitAssignment
This is an assignment.


# STEPS USED TO DO THIS ASSIGNMENT:
I logged-in to my GitHub account.
Created a new repository called 'PLpBasicGitAssignment' and initialized it with a README file.
Created a new folder on my local machine called 'PLPBasicGitAssignment'.
Opened GitBash and navigated to the created folder.
Used 'git init' to initialize the empty git repository.
Used 'git remote add origin https://github.com/MiriamWaithira/PLpBasicGitAssignment.git' to connect the local repository to the GitHub repository.
Used 'code .' to open VSCode.
Created 'hello.txt' in the folder and added a message in that file.
At this point my terminal was still in the master branch. To check the current branch 'git branch' whose output was *master.
To rename the branch from master to main 'git branch -m master main'.
To verify the remote repository connected 'git remote -v'.
To avoid creating a merge conflict, I used 'git pull origin main --rebase'.
Staged the 'hello.txt' file I had created using 'git add hello.txt'.
Added a commit message using 'git commit -m "Added hello.txt with a greeting"'.
To push the changes to my remote repository, I used 'git push -u origin main'.
On the github repository I had created, the 'hello.txt' file and the commit message are visible.
