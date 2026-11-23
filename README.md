# SplitSmart
A group expense manager written in C. It tracks who paid what, works out each person's balance, and suggests the smallest set
of payments to settle everyone up.

## Features
- Add expenses paid by any friend (2-10 friends)
- View total spend, equal share and each person's balance
- Sort balances using bubble sort
- Smart settlement using a greedy algorithm and a graph
  (adjacency matrix) of who pays whom

## How to run
gcc main.c -o main
./main
