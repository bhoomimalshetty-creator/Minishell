# Minishell
Mini Shell is a Linux-based command-line interpreter developed in C. It provides a shell-like environment to execute user commands and demonstrates Linux system programming concepts such as process creation, inter-process communication, signals, pipes, file descriptors, and process synchronization.

## Features

- Execute Linux commands
- Built-in command support
- Process creation using `fork()`
- Command execution using `exec()`
- Parent-child synchronization using `waitpid()`
- Pipe implementation
- Input/output redirection
- Signal handling
- Background process handling
- File descriptor management

## Technologies Used

- C Programming
- Linux
- System Calls
- Process Management
- Inter-Process Communication (IPC)
- Signals
- Pipes
- File Descriptors

## System Calls Used

```text
fork()
execvp()
waitpid()
pipe()
dup()
dup2()
open()
close()
signal()
