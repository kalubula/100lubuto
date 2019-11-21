
Task 3: A step-by-step tutorial on how to use GitFlow process with GIT and Github to collaborate
 - [x] Changing and adding files
	#### To work with files first create a text file called myfile.txt in the directory 100lubuto 
	#### The command to create a text file in windows powershell is :
	cd >myfile.txt
	#### To navigate to myfile.txt use the command:
	start myfile.txt
	#### The image below demonstates the result of running the command, an empty myfile.txt is open for edit.
	     Snapshot of file being created in powershell and shown in windows explorer:
    ![ Creating file image ](/images/file.png)
	#### To navigate to myfile.txt use the command:
	start myfile.txt
	#### The empty file will be openned in notedpad and can be edited:
	![ Open file with powershell ](/images/open_file.png)
	#### After successfully adding files you can change to the file you want to edit.
	#### First list the files in your directory to see the files you have by using the command:
	dir
	#### The snapshot demonstates the use of the command dir to list the files:
	![ list of files ](/images/list.png)
	#### After navigating to the file of your choice you can stage for commit using git by running:
	git add myfile.txt
	![ Staging file for commit ](/images/stage_file.png)
	#### And commit it 
	git commit -m "Fix"
	#### Where -m is the commit message
	#### Finally push you changes the to github respository on master branch or specific branch:
	git push origin master
	
 - [x] checkout repository from GitHub
	#### To get a copy of the repository to your local machine you can run the following command:
	git clone https://github.com/Lindo21/
	#### You can navigate to a specific branch on git by using:
	git checkout branch_name
	#### Where branch_name is the name of your branch
 - [x] Tags and release
	#### You can list the existing tags by using the command :
	git tag
	#### Git supports two types of tags: Annotated tag and lightweight
	#### To create an Annotated tag  specify -a when you run the tag command::
	git tag -a v1 -m "Version 1"
	#### You can run git show to see details of your tag v1:
	git show v1
	#### Lightweight tags
	#### To create a tag just provide a tag:
	git tag v1
	#### Sharing tags:
	##### Tags can be pushed to the server to be shared by running:
	git push origin tag_name
    ### For more resources on Markdown:
	[Markdown](https://guides.github.com/features/mastering-markdown/#examples)
	### For resources on git tagging:
	[Tagging](https://git-scm.com/book/en/v2/Git-Basics-Tagging)