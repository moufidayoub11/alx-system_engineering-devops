# 0x03-shell_variables_expansions

This subdirectory contains scripts related to shell variables and expansions in the context of system engineering and DevOps.

## Scripts

Here is a list of the scripts included in this directory:

1. `0-alias`: A script that creates an alias with the name `ls` and value `rm *`.
2. `1-hello_you`: A script that prints hello user, where user is the current Linux user.
3. `2-path`: A script that adds `/action` to the PATH. `/action` is the last directory the shell looks into when looking for a program.
4. `3-paths`: A script that counts the number of directories in the PATH.
5. `4-global_variables`: A script that lists environment variables.
6. `5-local_variables`: A script that lists all local variables and environment variables, and functions.
7. `6-create_local_variable`: A script that creates a new local variable with the name `BEST` and value "SCHOOL".
8. `7-create_global_variable`: A script that creates a new global variable with the name `BEST` and value `SCHOOL`.
9. `8-true_knowledge`: A script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
10. `9-divide_and_rule`: A script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.
11. `10-love_exponent_breath`: A script that displays the result of `BREATH` to the power `LOVE`.
12. `11-binary_to_decimal`: A script that converts the number `BINARY` from base 2 to base 10.
13. `12-combinations`: A script that prints all possible combinations of two letters, except `oo`.
14. `13-print_float`: A script that prints the number `NUM` with two decimal places, followed by a new line.
15. `100-decimal_to_hexadecimal`: A script that converts the number `DECIMAL` from base 10 to base 16.
16. `101-rot13`: A script that encodes and decodes ASCII text using the rot13 encryption.
17. `102-odd`: A script that prints every other line from the input, starting with the first line.
18. `103-water_and_stir`: A shell script that adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result.

## Getting Started

To use these scripts, follow the instructions below:

1. Clone this repository to your local machine.
```
$ git clone https://github.com/moufidayoub11/alx-system_engineering-devops.git
```

2. Navigate to the `0x03-shell_variables_expansions` directory.
```
$ cd alx-system_engineering-devops/0x03-shell_variables_expansions
```

3. Choose the script you want to run and execute it using the shell.
```
$ ./script-name
```
Note: Replace `script-name` with the actual name of the script you want to run.

## Resources

For more information on shell variables and expansions, you may find the following resources helpful:

- [Bash Variables](https://tldp.org/LDP/abs/html/variables.html)
- [Bash Parameter Expansion](https://www.gnu.org/software/bash/manual/bash.html#Shell-Parameter-Expansion)
- [Understanding Bash Variables](https://www.linuxjournal.com/content/understanding-bash-variables)
- [Using Bash Variables in Your Script](https://www.hostinger.com/tutorials/bash-scripting#3-Using-Variables)
- [Parameter Expansions in Bash](https://www.baeldung.com/linux/parameter-expansions-in-bash)

