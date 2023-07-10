# 0x02 - Shell, I/O Redirections and filters

This subdirectory contains scripts related to shell I/O redirections and filters in the context of system engineering and DevOps.

## Scripts

Here is a list of the scripts included in this directory:

1. `0-hello_world`: Prints "Hello, World", followed by a new line to the standard output.
2. `1-confused_smiley`: Displays a confused smiley `"(Ôo)'`.
3. `2-hellofile`: Display the content of the `/etc/passwd` file.
4. `3-twofiles`: Display the content of `/etc/passwd` and `/etc/hosts`.
5. `4-lastlines`: Display the last 10 lines of `/etc/passwd`.
6. `5-firstlines`: Display the first 10 lines of `/etc/passwd`.
7. `6-third_line`: Display the third line of the file `iacta`.
8. `7-file`: Creates a file named exactly `\*\\'"Holberton School"\'\\*$\?\*\*\*\*\*:)` containing the text `Holberton School` ending by a new line.
9. `8-cwd_state`: Writes into the file `ls_cwd_content` the result of the command `ls -la`.
10. `9-duplicate_last_line`: Duplicates the last line of the file `iacta`.
11. `10-no_more_js`: Deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.
12. `11-directories`: Counts the number of directories and sub-directories in the current directory.
13. `12-newest_files`: Displays the 10 newest files in the current directory.
14. `13-unique`: Takes a list of words as input and prints only words that appear exactly once.
15. `14-findthatword`: Display lines containing the pattern “root” from the file `/etc/passwd`.
16. `15-countthatword`: Display the number of lines that contain the pattern “bin” in the file `/etc/passwd`.
17. `16-whatsnext`: Display lines containing the pattern “root” and 3 lines after them in the file `/etc/passwd`.
18. `17-hidethisword`: Display all the lines in the file `/etc/passwd` that do not contain the pattern “bin”.
19. `18-letteronly`: Display all lines of the file `/etc/ssh/sshd_config` starting with a letter.
20. `19-AZ`: Replace all characters `A` and `c` from input to `Z` and `e` respectively.
21. `20-hiago`: Removes all letters `c` and `C` from input.
22. `21-reverse`: Reverses its input.
23. `22-users_and_homes`: Displays all users and their home directories, sorted by users.
24. `100-empty_casks`: Finds all empty files and directories in the current directory and all sub-directories.
25. `101-gifs`: Lists all the files with a `.gif` extension in the current directory and all its sub-directories.
26. `102-acrostic`: Decodes acrostics that use the first letter of each line.
27. `103-the_biggest_fan`: Parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

## Getting Started

To use these scripts, follow the instructions below:

1. Clone this repository to your local machine:
```
$ git clone https://github.com/your_username/alx-system_engineering-devops.git
```

3. Navigate to the `0x02-shell_redirections` directory.
```
$ cd alx-system_engineering-devops/0x02-shell_redirections
```

3. Choose the script you want to run and execute it using the shell.
```
$ ./script-name
```
Note: Replace `script-name` with the actual name of the script you want to run.

## Resources

For more information on shell I/O redirections and filters, you may find the following resources helpful:

- [I/O Redirection](http://linuxcommand.org/lc3_lts0070.php)
- [Shell, I/O Redirection and Filters](https://www.ibm.com/docs/en/aix/7.2?topic=communications-shell-io-redirection-filters)
- [The Unix Shell: Redirection](https://swcarpentry.github.io/shell-novice/04-pipefilter/index.html)
