## Overview

BigShell is a POSIX-like shell program that demonstrates important process concepts. This project involves parsing command-line input, executing commands, implementing built-in commands, performing I/O redirection, managing shell variables, handling signals, and implementing job control.

## PLEASE NOTE
With OSU Student Conduct guidelines I will have to keep the code in a private Github Rep. 

## Features

- **Command Parsing**: Parse command-line input into executable commands.
- **External Commands**: Execute a variety of external commands as separate processes.
- **Built-in Commands**: Implement built-in shell commands like `cd`, `exit`, and `unset`.
- **I/O Redirection**: Perform various I/O redirection operations.
- **Shell Variables**: Assign, evaluate, and export shell variables.
- **Signal Handling**: Implement appropriate signal handling for the shell and executed commands.
- **Job Control**: Manage processes and pipelines using job control concepts.

## Screenshots

###Built-in Commands
#### Does the exit built-in work appropriately? 
![Screenshot 1](baseshell/bs1.png)
![Screenshot 2](baseshell/bs2.png)

## Learning Outcomes

- Describe and use the Unix process API.
- Write programs using the Unix API for signal handling and I/O redirection.
- Understand and implement job control and process management in a shell.

## Built-in Shell Utilities

- `cd`: Change the working directory.
- `exit`: Exit the shell.
- `unset`: Unset values of variables.

## Command Execution and Expansion

- **Command Words**: Expand command words.
- **Assignment Values**: Expand assignment values.
- **Redirection Filenames**: Expand redirection filename operands.

## I/O Redirection Operators

- `>`: Redirect output.
- `<`: Redirect input.
- `<>`: Open for reading and writing.
- `>>`: Append output.
- `>|`: Force output.
- `>&`: Duplicate output file descriptor.
- `<&`: Duplicate input file descriptor.

## Simple Commands

- **Foreground Commands**: Execute commands sequentially using `;`.
- **Background Commands**: Execute commands in the background using `&`.
- **Pipelines**: Execute commands in a pipeline using `|`.

## Job Control

- Manage and control jobs, including starting, stopping, and resuming jobs.

## Reference Documents

- **Builtins**: `cd(1)`, `chdir(3)`, `exit(1)`, `strtol(3)`, `unset(1)`, `getenv(3)`, `setenv(3)`.
- **Signal Handling**: `sigaction(3)`, `kill(2)`, `signal.h(0)`, `signal(7)`.
- **I/O Redirection**: `dup(2)`, `fcntl(3)`, `open(2)`.
- **Foreground/Background Commands**: `wait(2)`.
- **Pipelines**: `pipe(2)`.
- **Job Control**: `isatty(3)`, `setpgid(3)`, `getpgid(3)`, `tcsetpgrp(3)`, `tcgetpgrp(3)`.
- **General Purpose**: `ctype.h(0)`, `errno.h(0)`.

## Specifications

- Implement the BigShell command language, including quoting, token recognition, parameters, word expansions, redirection, and signal handling.
- Ensure robust error handling and user-friendly messages.

## Credits
Skeleton Code provided by Ryan Gambord, with Martin Nguyen implementing the 
- Built-in Commands

- Non-built-in commands

- Foreground/Background process waiting

- Redirection

- Pipelines

- Variable Assignment

- Signal Handling

- Job Control Functionality
