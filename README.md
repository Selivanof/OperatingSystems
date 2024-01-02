# Operating Systems Course 2023-2024
This is a repository for my submissions of the optional Operating Systems Course assignments during the academic year 2023-2024.

|   Course Information     |                           |
|--------------------------|---------------------------|
| Semester                 | 7                         |
| Attendance Year          | 2023-2024                 |
| Course Type              | Specialization            |
| Department               | Electronics and Computers |
| Project Type             | Optional                  |

# Table of Contents
1. [Simple Linux Commands](#01-simple-linux-commands)
2. [Cleanup (Fish Shell)](#02-cleanup-fish-shell)
3. [Forks (C)](#03-forks-c)
4. [Signals and Git](#04-signals-and-git)
5. [TBA](#tba)


## 01. Simple Linux Commands

A very simple introduction to basic Linux commands. Includes creation of directories/files, file reading/writing and usage of pipes.

[More Details](https://github.com/Selivanof/os-course/tree/main/01.%20Simple%20Linux%20Commands)
## 02. Cleanup (Fish Shell)
A function written in fish shell that cleans up unused files after a specific amount of days of inactivity. The function's main features are:
1) Recursive directory cleaning flag.
2) Dry-run mode to display the files that would be deleted, without actually deleting them.
3) Exclude certain types of files and directories by name (can be more than one).
4) Sorting the files by either largest to smallest or opposite.
5) Adding a confirmation prompt before actually deleting.
   
[More Details](https://github.com/Selivanof/os-course/tree/main/02.%20Cleanup)
## 03. Forks (C)
A basic demonstration of forks in C.

A parent process forks 4 subprocesses. Each one of them gets a character as input from the user and reports it back to the parent process. When the parent receives all 4 inputs, it instructs the processes to print their received character in order of ascending PID. 

[More Details](https://github.com/Selivanof/os-course/tree/main/04.%20Signals%20and%20Git)
## 04. Signals and Git

#### a) Signals
A signal catcher that gracefully terminates the program upon receiving SIGINT and a "modified" signal catcher that catches SIGINT 2 times, after which it reverts to default handling of SIGINT.

#### b) Git
A simple introduction to Git and GitHub. This assignment involved the creation of a [separate repo](https://github.com/Selivanof/GitHashingExercise) and the usage of the Linux terminal to add/commit/push to both a local and the github repo.

[More Details](https://github.com/Selivanof/os-course/tree/main/03.%20Forks)
## 05. TBA
