
     ASSIGNMENT TWO - GROUP WORK (COLLABORATION)
	 
     Tasks: A step-by-step tutorial on how to use Vim to create and edit files from the Linux command line
	 Vim is a highly configurable text editor built to enable efficient text editing.
     It is an improved version of the vi editor distributed with most UNIX systems.
     Vim is useful for programming and it is like an entire IDE.
	 With vim errors are minimized what you enter is what you get. 
     Using text editors such as notepad or word can introduce characters difficult to read.
     By using the insert feature of vim, mistakes are reduced because you only insert when you enable
     the window to insert mode by pressing i. There is no room for special characters or spaces.
	 
	 To get started using vim go to docker Desktop switch to linux container and in settings switch shared to c:/
	 In docker download ubuntu server by using the powershell command:
	 docker pull ubuntu
	
	Start an interactive terrminal -t and mount the volume -v here:  my_vol. Use the command:
	docker run -i -t -v c:/src/my_vol ubuntu
	
	Install vim:
	
	First run apt-get update:
	apt-get update 
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

	
	