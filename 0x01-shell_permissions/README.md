# 0x01-shell_permissions

This subdirectory contains scripts related to shell permissions in the context of system engineering and DevOps.

## Scripts

Here is a list of the scripts included in this directory:

1. `0-iam_betty`: Changes the user ID to `betty`.
2. `1-who_am_i`: Prints the effective username of the current user.
3. `2-groups`: Prints all the groups the current user is part of.
4. `3-new_owner`: Changes the owner of the file `hello` to the user `betty`.
5. `4-empty`: Creates an empty file called `hello`.
6. `5-execute`: Adds execute permission to the owner of the file `hello`.
7. `6-multiple_permissions`: Adds execute permission to the owner and the group, and read permission to others for the file `hello`.
8. `7-everybody`: Adds execution permission to the owner, the group, and others for the file `hello`.
9. `8-James_Bond`: Sets the permission to 007 (read, write, and execute) for others, and no permissions for the group and the owner of the file `hello`.
10. `9-John_Doe`: Sets the mode of the file `hello` to `-rwxr-x-wx`.
11. `10-mirror_permissions`: Sets the mode of the file `hello` to the same mode of the file `olleh`.
12. `11-directories_permissions`: Adds execute permission to all users of every sub folder in working directory (only folders).
13. `12-directory_permissions`: Create a directory named `my_dir` with the permission `751`.
14. `13-change_group`: Changes the group of the file `hello` to the group `school`.
15. `100-change_owner_and_group`: Changes the owner and the group of the file `hello` to the user `vincent` and the group `staff`.
16. `101-symbolic_link_permissions`: Changes the owner and the group of the symbolic link `hello` to the user `vincent` and the group `staff`.
17. `102-if_only`: Changes the owner of the file `hello` to the user `vincent` only if it's current owner is `guillaume`.
18. `103-Star_Wars`: plays a star wars episode.

## Getting Started

To use these scripts, follow the instructions below:

1. Clone this repository to your local machine.
```
$ git clone https://github.com/moufidayoub11/alx-system_engineering-devops.git
```

2. Navigate to the `0x01-shell_permissions` directory.
```
$ cd alx-system_engineering-devops/0x01-shell_permissions
```

3. Choose the script you want to run and execute it using the shell.
```
$ ./script-name
```
Note: Replace `script-name` with the actual name of the script you want to run.

## Resources

For more information on shell permissions, you may find the following resources helpful:

- [Unix / Linux File Permission](https://www.tutorialspoint.com/unix/unix-file-permission.htm)
- [Linux File Permissions Explained](https://www.linux.com/training-tutorials/linux-file-permissions-explained/)
- [Understanding Linux File Permissions](https://www.linode.com/docs/guides/introduction-to-linux-permissions-and-ownership/)
