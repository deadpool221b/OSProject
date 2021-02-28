# OSProject
This is a self developed basic version of Bourne shell ("Bash") with multiple similar functionalities as well as many new ones.

## How To Run
Step 1. Download the source code to system in zip format or clone repo.

Step 2. On linux shell navigate to 
```
"Download-Location"/OSProject-main/OSProject-main/My-Shell
```
Step 3. compile the shell using command 
```
gcc shell.c linkedlist.h linkedlist.c utilities.h utilities.c color.h -o shell
```
Step 4. run using command 
```
./Shell
```

## Tech Stack Used
All the functionalities are programmed in C language with the help of libraries such as "sys/wait.h", "sys/types.h", "signal.h" ... etc.

## Important Logic Used
Basic functionality such as... 
* Executing commands and processed by forking the main process.
* Changing directory using "cd" command.
* Exiting the shell.
* Running and monitoring process in background.
* Manual as well as auto killing background process using signals.
* 
All these functionalities work smooth and bug free.

## Interesting Additions
* Command to change the color of text in terminal.
