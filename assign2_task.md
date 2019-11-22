
     ASSIGNMENT TWO - GROUP WORK (COLLABORATION)
	 
     Tasks: A step-by-step tutorial on how to use Vim to create and edit files from the Linux command line
	 Vim is a highly configurable text editor built to enable efficient text editing.
     It is an improved version of the vi editor distributed with most UNIX systems.
     Vim is useful for programming and it is like an entire IDE.
	 With vim errors are minimized what you enter is what you get. 
     Using text editors such as notepad or word can introduce characters difficult to read.
     By using the insert feature of vim, mistakes are reduced because you only insert when you enable
     the window to insert mode by pressing i. There is no room for special characters or spaces.
	 
	 First step install git for windows:
	Launch : 
	For first use configure git using the command git config --global user.name "Lindon"
	The other setting to configure is the email: git config --global user.email "lindonngonga@gmail.com"
	Check if the configurations are set correctly or not: git config --list
	At the bottom of the print out the username and email has been picked up the way I wanted to be picked up.
	pwd to see am the user
	Create a folder for my repository : mkdir git_repo
	Navigate to the folder created git_repo cd git_repo I use this folder for creating all other repositories.
	I will make my first repository called first_repo : mkdir first_repo
	Navigate to the empty folder 'first_repo': cd first_repo
	To create a repository run: git init This will create a hidden folder .git
	To create files within this folder use : Touch first_file.txt
	I can open it up in notepad: notepad first_file.txt
	and make some edits and save it.
	

	To get started using vim go run: apt-get update 
	and then run: apt-get install vim
	
	Start an interactive terrminal -t and mount the volume -v here:  my_vol. Use the command:
	docker run -i -t -v c:/src/my_vol ubuntu
	Then:
	apt-get install vim
	root@4f789aefb15d:/# cd my_vol
    root@4f789aefb15d:/my_vol# touch newfile.txt
    root@4f789aefb15d:/my_vol# vi newfile.txt
 - [x] Creating and adding content to the file
 
    #### Vim Command Description
     1. i	Enter insert mode
     1. x or Del	Delete a character
     1. X	Delete character is backspace mode
     1. u	Undo changes
     1. Ctrl + r	Redo changes
     1. yy	Copy a line
     1. dd	Delete a line
     1. :wq	quit and save changes

	
	