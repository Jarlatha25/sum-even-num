# sum-even-num
15.Write a python program to find the sum of first n even numbers.

n=int(input("enter the Limit :"))
s=0
for i in range (0,n+1,2):
    s=s+i
    print("The sum is : ",s)

Output:
enter the Limit :6
The sum is :  0
The sum is :  2
The sum is :  6
The sum is :  12
