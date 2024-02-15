SHELL - INIT FILES, VARIABLES & EXPANSIONS
	GitHub repository: holbertonschool-shell
	Directory: init_files_variables_and_expansions

TASKS :
0. <o> - Create a script that creates an alias.
	- Name: ls 
	- Value: rm *
	File: 0-alias 
		#!/bin/bash
		alias ls="rm *"
1. Hello you - Create a script that prints hello user, where user is the current Linux user.
	File: 1-hello_you 
		#!/bin/bash
		echo $USER
2. The path to success is to take massive, determined action - 	Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
	File: 2-path
		#!/bin/bash
		export PATH=$PATH:/action
3. If the path be beautiful, let us not ask where it leads - Create a script that counts the number of directories in the PATH.
	File: 3-paths
		#!/bin/bash
		echo $PATH | tr ':' '\n' | grep '/' | wc -l
4. Global variables - Create a script that lists environment variables.
	File: 4-global_variables
