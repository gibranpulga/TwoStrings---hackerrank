# TwoStrings---hackerrank
Two Strings kata from hackerrank - https://www.hackerrank.com/challenges/two-strings

------------------

Given two strings,  and , determine if they share a common substring.

Input Format

The first line contains a single integer, , denoting the number of  pairs you must check. 
Each pair is defined over two lines:

The first line contains string .
The second line contains string .
Constraints

 and  consist of lowercase English letters only.
Output Format

For each  pair of strings, print YES on a new line if the two strings share a common substring; if no such common substring exists, print NO on a new line.

Sample Input

2
hello
world
hi
world
Sample Output

YES
NO
Explanation

We have  pairs to check:

, . The substrings  and  are common to both  and , so we print YES on a new line.
, . Because  and  have no common substrings, we print NO on a new line.
