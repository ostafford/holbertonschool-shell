# Project 4 Notes and revision

## 0: ( `alias` )
**Question**: Create a script that creates an alias.
- Steps to break down:
    1. Select the correct command `alias`
    2. assign value
- Code Structure: ***(command -> long_command_name -> 'value')***
    1. `alias`
    2. `name='value'`
- ***Final Command***
	- `alias ls='rm *'`

## 01: ( `printenv` | `$ENVIRONMENT_VARIABLE` )
**Question**: Create a script that prints `hello user`, where user is the current Linux user.
- Steps to break down:
    1. Print `hello user`
    2. Current user
- Code Structure: ***(command -> )***
    1. `echo "hello_  "`
    2. `$ENVIRONMENT_VARIABLE`
- ***Final Command***
	- `echo "hello $USER"`

## 02: ( `export`  )
**Question**: Add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program.
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 03: ( `` )
**Question**: Create a script that counts the number of directories in the `PATH`.
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 04: ( `` )
**Question**: Create a script that lists environment variables.
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 05: ( `` )
**Question**: Create a script that lists all local variables and environment variables, and functions.
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 06: ( `` )
**Question**: Create a script that creates a new local variable.

Name: `BEST` Value: `School`
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 07: ( `` )
**Question**: Create a script that creates a new global variable.

Name: `Best` Value: `School`
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 08: ( `` )
**Question**: Write a script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 09: ( `` )
**Question**: Write a script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.

`POWER` and `DIVIDE` are environment variables
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 10: ( `` )
**Question**: Write a script that displays the result of `BREATH` to the power `LOVE`

`BREATH` and `LOVE` are environment variables\
The script should display the result, followed by a new line.
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 11: ( `` )
**Question**: Write a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable `BINARY`\
The script should display the number in base 10, followed by a new line
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 12: ( `` )
**Question**: Create a script that prints all possible combinations of two letters, except `oo`.

Letters are lower cases, from `a` to `z`\
One combination per line\
The output should be alpha ordered, starting with `aa`\
Do not print `oo`\
Your script file should contain maximum 64 characters
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 13: ( `` )
**Question**: Write a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable `NUM`.
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``

## 14: ( `` )
**Question**: Write a script that converts a number from base 10 to base 16.

The number in base 10 is stored in the environment variable `DECIMAL`\
The script should display the number in base 16, followed by a new line
- Steps to break down:
    1. 
    2. 
- Code Structure: ***()***
    1. ``
    2. ``
- ***Final Command***
	- ``


# Command List

### `'alias'`
#### Structure
- Command -> Option -> Name -> Assignment_Operator(=) -> New_command
- `alias [option] [name[=value]]`
#### Example
- `alias ls='rm *'`
#### Breakdown
- `alias`:\
Used to create shortcuts(nicknames) for long form commands.\
Allows you to assign custom command or modify an existing command.
- `ls` (`[name]`):\
This is the [name] of the alias that is being created.\
`ls` is a default used command however in this example we are changing its `[=value]`
- `=`:\
This is the ***assignment operator*** that links the `[name]` to the command `[=value]`
- `rm *` (`[=value]`):\
This is the ***new command*** you're assigning to the alias `[name]`

#### Plain English
- `ls` is still called `ls` however it now has the value of deleting files instead of listing them.
#### Reference
- https://linuxcommand.org/lc3_man_pages/aliash.html
- https://ss64.com/bash/alias.html


### `'echo'`
#### Structure
- Command -> Option -> String
- `echo [option] [string]`
#### Example
- `echo "Hello World"`\
~/ Hello World
- `echo "Hello $USER"`\
~/ Hello John
#### Breakdown
- `echo`:\
The command to ***print*** text or ***standard output***
- `"..."` (string):\
This is the ***argument*** that is ***passed*** to the `echo` command.\
It is enclosed in double quotes which will treat it as a single string that may contain ***variables***
- 
#### Plain English
#### Reference
- https://linuxcommand.org/lc3_man_pages/echoh.html
- https://ss64.com/bash/echo.html



### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference

### `'command_name'`
#### Structure
#### Example
#### Breakdown
#### Plain English
#### Reference
