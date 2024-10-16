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
	- Command structure `rm [.file/PATH]`

## 9-firstdirdeletion
the `rm -r` command will allow you to delete the directory of choice
	- Command structure `rm -r [.file/PATH]

## 10-back
the `cd -` command will bring you back to the previous working directory.
	- For example `cd /destination_1` will bring you to the folder `destination_1` then if i run a new command `cd /destination_2/destination_3` then i would be in a different directory location to `destination_1`. That being said if i were to run `cd -` I'll be able to go back to my previous `pwd` which was `destination_1` instead of the standard `cd ..` which will just go back one file in the current PATH.

## 11-lists
the `ls` command will list the files in the current directory that you are in. however there are further commands that can be used together is `ls`.
	- `ls` command structure `ls [option] [color] [format] [file/PATH]`
	- so in this case `l` indicated long format, `a` indicates files or folders that begin with a `.`
	- `file/PATH` you can have mulitple PATHs when seperated with a space inbetween each other.

## 12-file_type
the `file` command wil print the type of file that is executed in the command
	- Command structure `file [file/PATH]`

