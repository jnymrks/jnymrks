# Project 1 Test Documentation

## Overview

This document outlines the testing procedures and results for the Project 1 implementation, including tests for `MyCopy`, `ForkCopy`, `PipeCopy`, `shell`, `MergesortSingle`, and `MergesortMulti` programs.


## Test Procedures

Each program was tested with various inputs to ensure correct functionality and performance. The tests aimed to cover typical, boundary, and error cases.

---

### MyCopy Test
In this test, I wrote a python program to randomly generates the string with ASCII letters. The size of the string was from 1KiB to 16MiB. The text files and the python file are in `Copy/test_txt` directory. 
In all cases, the output was correct and also for the edge cases(like text file with no letters), it worked well.

### ForkCopy Test
Same as above.

### PipeCopy Test
Same as above.

---

### Shell Test
#### Test Case 1: ls

**Input**: `ls`

**Expected Output**: All the files in the directory is listed

**Actual Output**: Successfully executed.

#### Test Case 2: cd

**Input**: `cd DIR_NAME`
**Expected Output**: Move to the directory(`DIR_NAME`) 
**Actual Output**: Successfully executed.

#### Test Case 3: pipe

**Input** `ls -l | wc`
**Expected Output**: Count the word of `ls -l` output.
**Actual Output**: Successfully executed.

I could only finish the basic requirement due to the lack of time. I should have started earlier to complete all the work given. That is one thing I regret about. Also I couldn't implement the part that we have "two or more pipes". I could only do with the command that has only one pipe. 
---

### MergesortSingle Test
In this test, I wrote a python program to randomly generates the integers within the required range. The length of the list was from 8 to 1000000. The text files and the python file are in `Sort/test_txt` directory. 
In all cases, the output was correct and also for the edge cases(like text file with no letters), it worked well.


### MergesortMulti Test
Same as above.

---

## Performance Analysis

### Mergesort Performance

The performance of `MergesortSingle` and `MergesortMulti` was analyzed by sorting arrays of various lengths with different numbers of threads. The results are shown in the `report.pdf`.

### Copy Program Performance

The execution time of `MyCopy`, `ForkCopy`, and `PipeCopy` was compared across different buffer sizes and file sizes. The results are shown in the `report.pdf`.
