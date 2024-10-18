# I/O Redirection and Filters

## 0-hello_world
`echo`	- will print the string (text) that you put in between single or double quotes

## 2-hellofile
`cat`	- concatenate and print files. Effectively will showcase the files content.\
	- You can also display multiple files by incoroprating a space inbetween each file name or location.

## 4-lastlines
`tail`	- display the last part of a file.\
	- That being said the `-n` option will allow you to set the number of lines that you want to view. **Understand that the last line is considered line 1 instead of the last line**

## 5-firstlines
`head`	- Will do the same as `tail` but for the beginning of the file.

## 6-third_line
Pipe (`|`)\
- The pipe allows you to take the output of one command and pass it as input to another command\
	- *eg.* syntax structure `head -n 3 file_name | tail -n 1`\
		- `head -n 3` is like flipping to the first 3 pages of a book.\
		- `tail -n 1` then says, "Give me the last page of these 3 pages."

## 7-file
Redirection *single* (`>`)\
- **The "Redirection"** will pass the *output* before it and write it into the file.\
	- When using **redirection**, it's important to remember that the output will always go to a file and not another command.\
	- To connect or chain multiple commands, use the *pipe* (`|`) operator.\
	- *eg.* syntax structure `echo "Content of the file goes here" > file_name.txt`\
		- `echo "..."` is the command to print/display your text/string\
		- `>` will redirect that command into the file "file_name.txt"\

Redirection *double* (`>>`)\
- Double Redirection (>>) functions similarly to single redirection (>), but instead of overwriting the existing content of a file, it appends or adds new output to the end of the file.


## 8-cwd_state
	- This is an extension from tasks 6 and 7. I realized that you can run a command and directly redirect its output into a file without needing an additional step to "print" or "write." Using redirection allows you to input the output results straight into a file.

  
