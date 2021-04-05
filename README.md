# Introduction-To-Python

Q1. Given an integer n perform the following conditional actions: • If n is odd, print Weird • If n is even and in the inclusive range of 2 to 5 , print Not Weird • If n is even and in the inclusive range of 6 to 20, print Weird • If n is even and greater than 20, print Not Weird

n=int(input("Enter any number:"));
if n%2!=0:
    print("Weird")
else:
    if n>=2 and n<=5:
        print("Not Weird")
    elif n>=6 and n<=20:
        print("Weird")
    elif n>20:
        print("Not weird")


Q2. WAP to read an integer ‘n’ from STDIN. For all non-negative integers i<n, print i**2 on a separate line.

n=int(input("Enter any number:"));
for i in range(0,n):
    i=i**2
    print(i)


Q3. WAP to read an integer from STDIN. Without using any string methods, print the following on a single line: 123…n

n=int(input("Enter any number:"));
for i in range(1,n+1):
    print(i, end="")
