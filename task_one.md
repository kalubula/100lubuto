Task 1:A reference guide that demonstrates at least 10 commands used to work with GIT, Docker, PowerShell, and Bash respectively.
 GIT COMMANDS:
The command to *initialize* the GIT repository is:
	git init
	[Screenshot of git clone example](/images/git_clone.png)
To put the markdown file 'task_one.md' on the stage the command to use is:
	git add task_one.md
	[Screenshot to put git on stage}(/images/git_add.png)
Whenever ther is a modification on the task_one.md file run git status to check the status of modifications.
    [Screenshot to demonstrate git status command](/images/git_status.png)
To commit any files added with git add command and files changes the command:
	git commit is used
	[Snapshot of git commit command -m is used to enter the message](/images/git_commit.png)
Before sending my files to github I can run to check if I have origin by using the command:
	git push origin master
	[Checkout the snapshot for git remote show](/images.git_remote_show.png)
Another variation of the command to show the origin to show the original github repository.
   git remote show origin
   [The snapshot for git remote show origin command](/images/git_remote_show_origin.png)
To push back to the origin(gitHub) the command
	git push origin master
	[The command showing the operation to take my changes and send back to gitHub](/images/git_push_origin_master.png)
Where origin is github and master the name of the branch
