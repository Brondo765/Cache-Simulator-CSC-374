# Cachelab-handout

## Before running the autograders, compile your code:
- make

## Check the correctness of your simulator:
- ./test-csim

## Check the correctness and performance of your aoat functions:
- ./test-aoat -N 32
- ./test-aoat -N 64
- ./test-aoat -N 67

## Check everything at once (this is the program that your instructor runs):
- ./driver.py    

## You will modifying and handing in these two files
- csim.c: *Your cache simulator*
- aoat.c: *Your aoat function*

## Tools for evaluating your simulator and aoat function
- Makefile: *Builds the simulator and tools*
- README: *This file*
- driver.py*: *The driver program, runs test-csim and test-aoat*
- cachelab.c: *Required helper functions*
- cachelab.h: *Required header file*
- csim-ref*: *The executable reference cache simulator*
- test-csim*: *Tests your cache simulator*
- test-aoat.c: *Tests your aoat function*
- tracegenaoat.c: *Helper program used by test-aoat*
- traces/: *Trace files used by test-csim.c*
