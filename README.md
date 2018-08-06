# Implementation of Game of Life using OpenMP
1. Assign random values to each matrix element (0-dead, 1-alive)
1. Change the state of each element using its current state and the states of its 8 neighbours:
   * if there are 5 or more 1s, change its state to alive 
   * otherwise change its state to dead
1. Repeat (2) at least 10 times and observe the changes in the matrix.
