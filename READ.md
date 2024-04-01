# Project 1: Implementing Concurrency with Linux Processes and Threads

## Overview

This project focuses on designing and implementing systems programs using the C language, with a specific emphasis on Linux system calls for process control and management, concurrent execution of processes, and the use of POSIX Pthread library for concurrency.

## Files

### Copy Directory

- **ForkCopy.c**: Implements a file copy operation by creating a new process using the `fork` system call and executing the copy operation in the child process.
- **MyCopy.c**: A simple file copy program that copies the content of one file to another using basic file manipulation system calls.
- **PipeCopy.c**: Demonstrates inter-process communication by copying file content from one file to another using a pipe between two forked processes.

### Shell Directory

- **shell.c**: A shell-like program that can execute commands with arguments and commands connected by pipes, illustrating how Linux spawns processes.
- **shellServer.c**: Extends `shell.c` by implementing a server that allows multiple clients to connect and execute commands remotely using Internet-domain sockets.

### Sort Directory

- **MergesortMulti.c**: Implements the mergesort algorithm using multiple threads to sort a large dataset, demonstrating the use of Pthreads for concurrency.
- **MergesortSingle.c**: A single-threaded implementation of the mergesort algorithm for sorting large datasets.

### Additional Files

- **plot_data.py (in both Copy and Sort directories)**: A Python script used for generating visualizations of the execution time of different program implementations under various configurations.
- **test_txt (in both Copy and Sort directories)**: Contains test files and scripts used for generating input data for testing the file copy and sorting implementations.
