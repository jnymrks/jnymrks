# Project 1 Test Documentation

## Overview

This document outlines the testing procedures and results for the Project 1 implementation, including tests for `MyCopy`, `ForkCopy`, `PipeCopy`, `shell`, `MergesortSingle`, and `MergesortMulti` programs.


## Test Procedures

Each program was tested with various inputs to ensure correct functionality and performance. The tests aimed to cover typical, boundary, and error cases.

### MyCopy Test
In this test, I wrote a python program to randomly generates the string with ASCII letters. The size of the string was from 1KiB to 16MiB. The text files are in `Copy/test_txt` directory. 
In all cases, the output was correct and also for the edge cases(like text file with no letters), it worked well.

### ForkCopy Test
Same as above.

### PipeCopy Test
Same as above.

### Shell Test
#### Test Case 1: ls

**Input**: `ls`

**Expected Output**: All the files in the directory is listed

**Actual Output**: Successfully executed.

#### Test Case 2: cd

**Input**: `cd DIR_NAME`
**Expected Output**: Move to the directory(`DIR_NAME`) 
**Actual Output**: Successfully executed.

####Test Case 3: \|
**Input** `ls -l | wc`
**Expected Output**: Count the word of `ls -l` output.
**Actual Output**: Successfully executed.

### MergesortSingle Test

...

### MergesortMulti Test

...

## Performance Analysis

### Mergesort Performance

The performance of `MergesortSingle` and `MergesortMulti` was analyzed by sorting arrays of various lengths with different numbers of threads. The results are shown in the `report.pdf`.

### Copy Program Performance

The execution time of `MyCopy`, `ForkCopy`, and `PipeCopy` was compared across different buffer sizes and file sizes. The results are shown in the `report.pdf`.

