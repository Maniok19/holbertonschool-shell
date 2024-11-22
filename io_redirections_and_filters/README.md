# I/O Redirections and Filters

Welcome to the I/O Redirections and Filters directory of the Holberton School Shell Projects. This directory contains various shell scripts that demonstrate how to manage input and output redirections, as well as how to use filters to process data in a Unix-like operating system.

## Table of Contents
- [Overview](#overview)
- [Scripts](#scripts)
- [Usage](#usage)
- [Author](#author)

## Overview
In this directory, you will find scripts that cover the following topics:
- Redirecting output to files
- Using pipes to connect commands
- Filtering text with commands like `grep`, `head`, and `tail`

## Scripts
Here is a list of the scripts included in this directory:
- `0-hello_world`: Prints "Hello, World" to the standard output.
- `2-hellofile`: Displays the content of the `/etc/passwd` file.
- `3-twofiles`: Displays the content of the `/etc/passwd` and `/etc/hosts` files.
- `4-lastlines`: Displays the last lines of the `/etc/passwd` file.
- `5-firstlines`: Displays the first lines of the `/etc/passwd` file.
- `6-third_line`: Displays the third line of the `iacta` file.
- `7-file`: Creates a file with a specific content.
- `8-cwd_state`: Redirects the output of `ls -la` to a file.
- `9-duplicate_last_line`: Appends the last line of `iacta` to the same file.
- `18-letteronly`: Filters lines in the `/etc/ssh/sshd_config` file that start with a letter.
- `23-empty_casks`: Finds and prints the names of empty files in the current directory.
- `25-acrostic`: Creates an acrostic from the first character of each line of input.

## Usage
To use any of these scripts, simply run them in your terminal. For example, to display the content of the `/etc/passwd` file using the `2-hellofile` script, you would run:
```bash
./2-hellofile
```
Make sure you have the necessary permissions to execute the scripts and perform the actions they describe.

## Author
Mano Delcourt

These scripts are part of the Holberton School curriculum and are designed to provide hands-on experience with managing I/O redirections and using filters. Happy coding!