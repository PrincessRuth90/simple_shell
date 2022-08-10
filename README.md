# simple_shell

# A simple C shell project

# List of allowed functions and system calls
 
* access (man 2 access)
* chdir (man 2 chdir)
* close (man 2 close) 
* closedir (man 3 closedir)
* execve (man 2 execve)
* exit (man 3 exit)
* _exit (man 2 _exit)
* fflush (man 3 fflush)
* fork (man 2 fork)
* free (man 3 free)
* getcwd (man 3 getcwd)
* getline (man 3 getline)
* getpid (man 2 getpid)
* isatty (man 3 isatty)
* kill (man 2 kill)
* malloc (man 3 malloc)
* open (man 2 open)
* opendir (man 3 opendir)
* perror (man 3 perror)
* read (man 2 read)
* readdir (man 3 readdir)
* signal (man 2 signal)
* stat (__xstat) (man 2 stat)
* lstat (__lxstat) (man 2 lstat)
* fstat (__fxstat) (man 2 fstat)
* strtok (man 3 strtok)
* wait (man 2 wait)
* waitpid (man 2 waitpid)
* wait3 (man 2 wait3)
* wait4 (man 2 wait4)
* write (man 2 write)

# Description

This is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh). Additional functions are also included. This program is been written entirely in C as a milestone project for Alx School.

# Compilation

Our shell is been compilled using gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

# Usage

After compilation, the resulting program can run stand-alone, either in interactive or non-interactive mode.

# Interactive Mode 

In interactive mode, simply run the program and wait for the prompt to appear. From there, you can type commands freely, exiting with either the "exit" command or ctrl-D.

# Non-Interactive Mode

In non-interactive mode, echo your desired command and pipe it into the program like this: echo "ls" | ./shell In non-interactive mode, the program will exit after finishing your desired command(s). This is the man page which contains all functions and descriptions of all the functions used in this Simple shell project. To access this page, Do:

# Authors

This file contains the details of all the individuals that contributed to this shell project.

# Features

1. DIsplay a prompt and wait for the user to type a command. A command-line always ends with a new line.

2. The prompt is displayed again each time a command has been executed.

3. The command lines are simple, no semicolons, no pipes, no redirections, or any other advanced features.

4. The command lines are made only of one word.No arguement will be passed to the programs.

5. If an executable is not found the shell prints an error message and display the prompt again.

# Credits

All codes been written by Marcus Ruth and Micheal Oriyomi
