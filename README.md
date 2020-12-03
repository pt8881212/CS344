# CS344
Program 1: 
lists movies by year,language, and ratings entered
*****************************************************************************************************************************
Program 2: 

reading and writing files and directories on Unix.
*****************************************************************************************************************************
Program 3:

write smallsh, your own shell in C. smallsh will implement a subset of features of well-known shells, such as bash. 
Program will
Provide a prompt for running commands
Handle blank lines and comments, which are lines beginning with the # character
Provide expansion for the variable $$
Execute 3 commands exit, cd, and status via code built into the shell
Execute other commands by creating new processes using a function from the exec family of functions
Support input and output redirection
Support running commands in foreground and background processes
Implement custom handlers for 2 signals, SIGINT and SIGTSTP
*****************************************************************************************************************************
program 4:

use of threads, mutual exclusion and condition variables
creates 4 threads to process input from standard input as follows

Thread 1, called the Input Thread, reads in lines of characters from the standard input.
Thread 2, called the Line Separator Thread, replaces every line separator in the input by a space.
Thread, 3 called the Plus Sign thread, replaces every pair of plus signs, i.e., "++", by a "^".
Thread 4, called the Output Thread, writes this processed data to standard output as lines of exactly 80 characters.
Furthermore, in your program these 4 threads must communicate with each other using the Producer-Consumer approach. 
*****************************************************************************************************************************
program 5:

creating five small programs that encrypt and decrypt information using a one-time pad-like system. These programs will combine 
the multi-processing code you have been learning with socket-based inter-process communication. Your programs will also be accessible 
from the command line using standard Unix features like input/output redirection, and job control. Finally, you will write a short
compilation script.
