# 0x00-shell_basics

This subdirectory contains scripts related to basic shell commands and navigation in the context of system engineering and DevOps.

## Scripts

Here is a list of the scripts included in this directory:

1. `0-current_working_directory`: Prints the current working directory.
2. `1-listit`: Displays the contents of the current directory.
3. `2-bring_me_home`: Changes the working directory to the user's home directory.
4. `3-listfiles`: Displays the contents of a directory in a long format.
5. `4-listmorefiles`: Displays the contents of a directory, including hidden files.
6. `5-listfilesdigitonly`: Displays the contents of a directory in a long format, with user and group IDs displayed numerically.
7. `6-firstdirectory`: Creates a directory called `holberton` in the `/tmp/` directory.
8. `7-movethatfile`: Moves the file `betty` from the `/tmp/` directory to the `/tmp/holberton/` directory.
9. `8-firstdelete`: Deletes the file `betty` from the `/tmp/holberton/` directory.
10. `9-firstdirdeletion`: Deletes the directory `holberton` that is in the `/tmp/` directory.
11. `10-back`: Changes the working directory to the previous one.
12. `11-lists`: Lists all files, including hidden files, in the current directory and its parent directory and the `/boot/` directory.
13. `12-file_type`: Prints the type of the file named `iamafile` in the `/tmp/` directory.
14. `13-symbolic_link`: Creates a symbolic link to `/bin/ls`, named `__ls__`.
15. `14-copy_html`: Copies all HTML files from the current working directory to the parent directory, but only those that did not exist in the parent directory or are newer than the versions in the parent directory.
16. `100-lets_move`: Moves all files beginning with an uppercase letter to the directory `/tmp/u`.
17. `101-clean_emacs`: Deletes all files in the current working directory that end with the character `~`.
18. `102-tree`: Creates the directories `welcome/`, `welcome/to/`, and `welcome/to/holberton` in the current directory.
19. `103-commas`: Lists all files and directories in the current directory, separated by commas.

## Getting Started

To use these scripts, follow the instructions below:

1. Clone this repository to your local machine.
```
$ git clone https://github.com/moufidayoub11/alx-system_engineering-devops.git
```

2. Navigate to the `0x00-shell_basics` directory.
```
$ cd alx-system_engineering-devops/0x00-shell_basics
```

3. Choose the script you want to run and execute it using the shell.
```
$ ./script-name
```
Note: Replace `script-name` with the actual name of the script you want to run.

## Resources

For more information on shell basics, you may find the following resources helpful:

- [Introduction to the Unix command line](https://learnxinyminutes.com/docs/bash/)
- [Linux Shell Scripting Tutorial](https://bash.cyberciti.biz/guide/Main_Page)
- [Bash Scripting Tutorial](https://linuxconfig.org/bash-scripting-tutorial-for-beginners)
