# SIMPLE SHELL
---

## INTRODUCTION:

This repository is one of the many ALX-Software Engineering School Project. The project is aimed at teaching students how a shell works and its implementation in using C programming language. A limited number of standard library functions were used, instead most functions were implemented using knowledge acquired over the past three months.

	> PHEEEW! it's been a rough one.. but it is interesting!

## The objective of this project in addittion to understanding and implementing our own shell programme, is to also give understanding of the working principles of the operating system, function call, system calls, applications running modes and privileges and to also increase our collaboration skills and etiquette.
---

## USAGE

In order to run this program,

	1. Clone This Repo

	2. git clone git@github.com/ShukrahOdeyemi1/simple_shell.git

	3. compile it with

		> gcc 4.8.4 -Wall -Werror -Wextra -pedantic *.c -o (your preffered executable name)

	4. You can then run it by invoking ./(your preffered executable name) in that same directory.
---

## HOW TO USE IT

After you have run your executable generated, a prompt with **$** will be displayed and the shell is ready to take your commands.

	> $  _type your commands here_

This shell can handle two kinds of commands: 
	* builtins and 
	* user defined executables program.

### List of built-ins
Built in commands supported includes:

	* cd [directory]: Switch to the specified directory (path).
	* env: Displays the environment variable
	* getenv NAME: Return the value of the NAME variable if it is in the environment
	* help [command]: Displays the syntax for the command, or all commands.
	* variable replacement: echo $$, $? and $PATH Return pid, exit status of terminated program and PATH respectively.

> IMPORTANT TO NOTE:
> The shell will not close when user sends the interrupt signal (signint) with ~***control + c***~ but with **control + d**

> If no argument is given to cd the command must be interpreted like cd $HOME

### List of functions and system calls we could use

List of allowed functions and system calls

* access (man 2 access)
* chdir (man 2 chdir)
* close (man 2 close)
* closedir (man 3 closedir)
* execve (man 2 execve)
* exit (man 3 exit)
* fork (man 2 fork)
* free (man 3 free)
* fstat (man 2 fstat)
* getcwd (man 3 getcwd)
* getline (man 3 getline)
* kill (man 2 kill)
* lstat (man 2 lstat)
* malloc (man 3 malloc)
* open (man 2 open)
* opendir (man 3 opendir)
* perror (man 3 perror)
* read (man 2 read)
* readdir (man 3 readdir)
* signal (man 2 signal)
* stat (man 2 stat)
* strtok (man 3 strtok)
* wait (man 2 wait)
* waitpid (man 2 waitpid)
* wait3 (man 2 wait3)
* wait4 (man 2 wait4)
* write (man 2 write)
* _exit (man 2 _exit)
---

## CUSTOM FUNCTIONS USED IN WRITING THE SHELL (Recreation of Standard Function in C)
* _strncpy
* _strlen
* _putchar
* _atoi
* _puts
* _strcmp
* _isalpha
* array_rev
* intlen
* _itoa
* _strcat
* _strcpy
* _strchr
* _strncmp
* _strdup
* _memcpy
* _calloc
* _realloc
* _getenv
* _getline
* _strtok
---

## EXIT: [exitstatus]
Exit from the program with exitstatus value. 0 by default.
---

Project Done in 15 Day
---

# AUTHORS:
OLAMIDE WILLIAMS [github.com/circleofwilliams] and

SHUKRAH ODEYEMI [github.com/ShukrahOdeyemi1]

