Simple Shell Project
This is a basic implementation of a shell program in C, which serves as a command-line interpreter for Unix-like systems.

Overview
A shell is a program that provides a command-line interface to interact with the operating system. This simple shell project demonstrates the fundamental concepts of how a shell operates. It can execute basic commands, handle signals, and manage background processes.

Files
simple_shell.c: This is the main C file containing the source code for the shell program.
utils.c and utils.h: These files contain utility functions used by the shell, such as string parsing and signal handling.
Makefile: The Makefile simplifies the build process. Use the command make to compile the program.
Features
Command Execution: The shell can execute simple commands with arguments (e.g., ls, echo Hello).

Exit: Typing exit will terminate the shell.

Signal Handling: The shell handles signals such as Ctrl+C (SIGINT) and Ctrl+Z (SIGTSTP).

Background Processes: Commands suffixed with & will run in the background.
