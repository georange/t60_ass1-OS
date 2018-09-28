# CSC 360 Assignment 1
Fall 2018  
Georgia Ma  
V00849447  
  
Enclosed in this submission are:  
 * PMan.c - the source code to my solution that will execute commands given by the user (detailed below).  
 * Makefile - to compile PMan.c with ease.  
 * inf.c - a testing function that prints a given tag at a given interval.  
 * args.c - a testing function that prints out all arguments passed to it.  

PMan supports 6 user-inputed commands:  
 * bg (program) (arguments) - to start background processes  
 * bglist - to print out a list of current background processes  
 * bgkill (pid) - to kill background processes by pid  
 * bgstop (pid) - to pause background processes by pid  
 * bgstart (pid) - to restart background processes by pid  
 * pstat (pid) - to print out a list of statistics and statuses by pid  

To run inf.c, run the commands:  
> gcc inf.c -o inf  
> ./inf (tag) (interval)  

To run args.c, run the commands:  
> gcc args.c -o args  
> ./args (any amount of arguments)  
  
To run PMan.c, run the commands:  
> make  
> ./PMan

