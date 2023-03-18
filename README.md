# Basic POSIX Threads Programming

This GitHub repository contains examples and explanations of basic POSIX Threads programming using C programming language.

## Introduction

POSIX Threads (also known as Pthreads) is a POSIX standard for threads programming. It defines a set of C programming language constructs that can be used to create and manipulate threads. Threads are lightweight processes that can run concurrently within a single process. By using threads, we can divide a complex task into smaller parts, which can be executed in parallel, thereby improving the overall performance of the application.

## Contents
This repository contains the following files:

```README.md``` This file provides an introduction and overview of the repository.<br />
```pthread_create.c``` This file demonstrates how to create a new thread using the pthread_create() function. <br />
```pthread_join.c``` This file demonstrates how to wait for a thread to complete its execution using the pthread_join() function. <br />
```pthread_shared_vars.c``` This file demonstrates how threads share memory <br />
```pthread_mutex.c``` This file demonstrates how to use a mutex to protect a critical section of code from concurrent access by multiple threads. <br />
```pthread_cond_wait.c``` This file demonstrates how to use a conditional variable to synchronize threads. <br />

## Prerequisites
To compile and run the code in this repository, you will need:

A C compiler (such as gcc)
A POSIX Threads library (such as pthreads) or OpenMP

## Usage

On Windows:
```
gcc file_name.c -fopenmp
```

On Unix/Linux:
```
gcc file_name.c
```

## Conclusion

This repository provides a starting point for learning about basic POSIX Threads programming. The examples provided here can be used as a reference for implementing multithreaded applications in C. If you have any questions or suggestions, feel free to open an issue or submit a pull request.

## License

[MIT](https://choosealicense.com/licenses/mit/)
