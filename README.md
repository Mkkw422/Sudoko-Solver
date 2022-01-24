
# Sudoko Solver

In this project, the user inputs a random board and the solved board is displayed after compilation.

## Description

The way this project works is, a user inputs values in the board and on compilation, if the board is valid, the solved board along with the initial board is displayed as output. This project consists of simple python commands with no additional libraries but works in a powerful manner by solving a ton of test cases by using backtracking algorithm. 

This board has '0' value assigned at places where it computes and stores possible values. As soon as it stores one value, it finds another empty slot('0') and applies constraints to check if a value can be stored. If it doesn't get a valid digit, it backtracks and changes the previous slot and starts computing again and finds the solution(provided the user has given a valid input).     



## Tech Stack

Python



