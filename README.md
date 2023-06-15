# 0x16. C - Simple Shell

**What is Shell?**  

The shell is the layer of programming that understands and executes the commands a user enters. In some systems, the shell is called a command interpreter. 

A shell usually implies an interface with a command syntax.   

This project is a simple version of the linux shell  

The shell should display a prompt, wait for the user to enter a command, execute the command, and display the prompt again. The shell should handle command lines with arguments and should handle the PATH to locate executables. It should also handle the "end of file" condition (Ctrl+D) and display error messages when an executable cannot be found.

**The project tasks involve implementing different features in the shell:**

Implement a basic version of the shell that meets the requirements specified in the project description.

Modify the shell to handle command lines with arguments.

Update the shell to handle the PATH variable and avoid calling fork if the command doesn't exist.

Implement the exit built-in command that allows the user to exit the shell.

Implement the env built-in command that prints the current environment.

Write your own getline function instead of using the standard getline function.

Avoid using strtok in your implementation.

Handle arguments for the built-in exit command.

Implement the setenv and unsetenv built-in commands to initialize, modify, or remove environment variables.

Implement the cd built-in command to change the current directory.

Handle the semicolon (;) operator to execute commands sequentially.

Handle the logical operators (&& and ||) to execute commands conditionally based on the success or failure of previous commands. 

**Collaborators**   

Lynne Michuki   

Diana Gatwiri


