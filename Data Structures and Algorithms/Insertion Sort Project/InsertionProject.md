# Insertion Sort => **[22,27,16,2,18,6]**

## Q1 - Write the stages of the above sequence according to the sort type.

[22,27,16,2,18,6]                           n

Stage 1 => [2,27,16,22,18,6]         (n-1)

Stage 2 => [2,6,16,22,18,27]         (n-2)

Stage 3 => [2,6,16,18,22,27]         (1)

## Q2- Write the Big-O notation.

n + (n-1) + (n-2) + 1 = n.(n+1) / 2

(n^2 + n)  / 2 = O (n^2)

## Q3- Write the Time Complexity.

[2,6,16,18,22,27]  

Average Case => 16,18

Worst Case => 27

Best Case => 2

## Q4 -Write in which state the number 18 enters after the array is sorted.

Average Case



## Q5- Write the first 4 steps of [7,3,5,8,2,9,4,15,6] according to Insertion Sort.

Stage 1 => [2,3,5,8,7,9,4,15,6]

Stage 2 => [2,3,4,8,7,9,5,15,6]

Stage 3 => [2,3,4,5,7,9,8,15,6]

Stage 4 => [2,3,4,5,6,9,8,15,7]



