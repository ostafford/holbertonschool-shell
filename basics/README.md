# holbertonschool-shell
Shell_basics


## 0-current_working_directory
the `pwd` command will prints the absolute path name of the current working directory

## 1-listit
the `ls` command Display the contents list of your current directory.

## 2-bring_me_home
the `cd ~` command changes the working directory to the user's home directory.
	- the `~` character also represents the home directory. 
	- the `$HOME` uses the variable environement method. eg `cd $HOME`.

## 3-listfiles 
the `ls -l` command will display current directory contents in a long format.

## 4-listmorefiles
the `ls -la` command will display current directory contents, including hidden files (starting with `.` ). Use the long format.

## 5-listfilesdigitonly
the `ls -lna` command will showcase the following content.
	- Long format `-l`
	- User and group IDs displayed numerically `-n`
	- Showcase hidden files (starting with '.') `-a`

## 6-firstdirectory
the `mkdir -p ./tmp/my_first_directory` command will create a script that creates a directory named my_first_directory in the /tmp/ directory
	- `mkdir`	Make the directory command
	- `-p`		Create intermediate directories as required.  If this option is not specified, the full path prefix of each operand must already exist.
			Meaning that if the directories exist it will pass them however what doesn't exist will be created with the `-p` mode written in the command line.
	- `./`		This is kind of like a `pwd`. essentially it specifies the current directory and will create the remainder of the path in the current directory.

## 7-movethatfile
the `mv` command wil move the file betty from /tmp/ to /tmp/my_first_directory.
	- That being said the structure of the `mv` command follows as `mv [file/PATH] [target/destination]`

## 8-firstdelete
the `rm` command will allow you to delete a file.
	- Command structure `rm [file/path]`

