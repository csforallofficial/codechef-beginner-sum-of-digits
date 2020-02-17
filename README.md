# codechef-beginner-sum-of-digits
You're given an integer N. Write a program to calculate the sum of all the digits of N.

Input
The first line contains an integer T, total number of testcases. Then follow T lines, each line contains an integer N.

Output
Calculate the sum of digits of N.

Constraints
1 ≤ T ≤ 1000
1 ≤ N ≤ 1000000
Example
Input
3 
12345
31203
2123
Output
15
9
8

solve:

t=int(input())
sum=0
for i in range(t):
    n=int(input())
    while(n>0):
        rem=n%10
        sum=sum+rem
        n=n//10
    print(sum)
    sum=0
        
