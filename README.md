## Algorithms
This repo contains algorithm questions I've come across, and my solutions in JavaScript.
### 1. Numeric string zeros
Input n is a decimal number n as a string. The function expand(n) transform it into an array of numbers (given as strings
again), such that each number has only one non-zero digit and their sum equals n.

Each number in the output array should be written without any leading and trailing zeros. And the elements in the array should be sorted in descending order.

###### Examples
For n = "7970521.5544" the output should be
`expand(n) = ["7000000", "900000", "70000", "500", "20", "1", ".5", ".05", ".004", ".0004"]`

For n = "7496314" the output should be
`expand(n) = ["7000000", "400000", "90000", "6000", "300", "10", "4"]`

And for n = "0"
`expand(n) = []`
### 2. Repeating substring
Input parameters are a string and a substring that is repeated inside the string. The function findRepeating(string, substring) returns the number of times substring is repeated inside string.
###### Examples
For string = "xyabcdfgabcsjhg" and substring = "abc" output should be
`findRepeating(string, substring) = 2`

### 3. Duplicates in array
Input is a sorted array of integers. The function findDuplicates(array) returns the number of times a sequence of duplicates appears in the array.
###### Examples
For array = [1,5,5,5,7,7,7,9] 5 and 7 are repeated, so output should be
`findDuplicates(array) = 2`

For array = [1,5,5,5,7,7,7,9,9] 5, 7 and 9 are repeated, so output should be
`findDuplicates(array) = 3`
