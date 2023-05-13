# CMPS 2200 Assignment 5
## Answers

**Name:** Roberto Duran


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**
    - It would be an algorithm that takes the largest denomination first that iterates through the denominations in descending order and selects the largest denomination that is $<=$ to the value left to be paid until the value left to be paid is



- **1b.**
    - O(log N)



- **2a.**
    - Assume we have available denominations {1, 3, 4} and we want to make change for 6. The algorithm would select 1 coin of value 4 and 2 coins of value 1 while the optimal solution is 2 coins of value 3.

- **2b.**
    - Using a 2D table that stores the minimum number of coins needed to make change for each value of N and k Where C(N, k) = infinity. The top-down approach we rely on memoization as a lookup reference to make sure the value hasnt been visited and recursively call C(N, k) and store the results in the table. For the bottom-up approach, we iterate through the table by rows starting at row 2, column 2 and calling on C(N, k) based on the previous values computed. Both have a work and span of O(Nk)



- **3a.**






- **3b.**






- **3c.**



