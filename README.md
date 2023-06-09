# Simple_shell
## Nadrian
* Simple shell project that simulates a simpler version of unix shell with built in commands.
  ![Simple_shell(1)](https://user-images.githubusercontent.com/107204057/232614526-1f34d7ce-8899-48d5-a431-4ff1688686cb.jpg)
# Table of Contents
* [Intro](#Intro)
* [Tech & Usage](#Technologies)
* [Requirements](#Requirements)
* [Testing](#Testing)
* [Learning Curve](#Learning)
* [Contact-Information](#Questions)
_____________________________________________________________________________________________
  # **Intro**: 
### **What is ***Nadrian***?** 
* Nadrian is a custom version of a unix terminal shell where the user can initialize on their computer and work through our command line interpreter version.
#### Function vs system call
- A function is a block of code that performs a specific task, while a system call is a request made by a program to the operating system with a specific permission. So a function call invokes the function, while a system call invokes an operating system request.
#### PATH
- `PATH` is an environment variable that instructs a system in which directories to search and run command or find executables through a specific path.
#### Exit
- `exit()` is a function that causes normal process termination and the least significant byte of status and 0377 is returned to the parent.

### **Visuals**: 

![Terminal - Concept](./client/src/images/png/logo-black.png)
![Program - Concept](./client/src/images/png/logo-white.png)
- A command line for new programmers using the CL tool.

## Technologies and Usage:
#### [C](https://www.w3schools.com/c/c_intro.php)

1. To install this application, `git clone` this repo.
2. Initialize the terminal by typing the command in the CL for an non interactive version or `init command` to start the shell in an interactive version.
3. Type `exit`or `CTRL + D` to terminate the program.
_____________________________________________________________________________________________
# Requirements
* Allowed editors: vi, vim, emacs
* All your files will be compiled on Ubuntu 20.04 LTS using `gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89`
* All your files should end with a new line
* A `README.md` file, at the root of the folder of the project is mandatory
* Your code should use the Betty style. It will be checked using `betty-style.pl` and `betty-doc.pl`
* Your shell should not have any memory leaks
* No more than 5 functions per file
* All your header files should be include guarded
* Use system calls only when you need to (why?)

# Testing:
* Shell should work like this in interactive mode:
```
$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$
```
* But also in non-interactive mode:
```
$ echo "/bin/ls" | ./hsh
hsh main.c shell.c test_ls_2
$
$ cat test_ls_2
/bin/ls
/bin/ls
$
$ cat test_ls_2 | ./hsh
hsh main.c shell.c test_ls_2
hsh main.c shell.c test_ls_2
$
```

# Learning Curve
### While creating this project we learned and practiced:
1. C language
2. SHELL basics.
3. File Input and Outputs.
4. Implement aux functions.
5. Implemented the functions and libaries to manage the app for both production and development environments.

## Questions?
For any questions about this repo, please contact us at: </br>
[nashalysf@gmail.com](mailto:nashalysf@gmail.com) </br>
[adria.morales@holbertonstudents.com](mailto:adria.morales@holbertonstudents.com)

To view more of our works, please visit out GitHub: </br> 
[nashalysf](https://github.com/nashalysf) </br>
[adrianmorales21](https://github.com/Adrianmorales21)
