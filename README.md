# hello-world
#first practice program in python
import math
import os
import random
import sys

N = int(raw_input().strip())

if N % 2 != 0:
    print "Weird"
else:
    if N >= 2 and N <= 5:
        print "Not Weird"
    elif N >= 6 and N <= 20:
        print "Weird"
    elif N > 20:
        print "Not Weird"
        
        
  if __name__ == '__main__':
    a = int(raw_input())
    b = int(raw_input())
    c= a+b
    d= a-b
    e=a*b
    print(c)
    print(d)
    print(e)
 
 if __name__ == '__main__':
    a = int(raw_input())
    b = int(raw_input())
    f=a//b
    g=a/b
    print(f)
    print(g)

if __name__ == '__main__':
    n = int(raw_input())
    for i in range(0,n):
        print(i*i)
        #print pow(i,2)
        
        
def is_leap(year):
    if year % 400 == 0:
        return True
    if year % 100 == 0:
        return False
    if year % 4 == 0:
        return True
    # Write your logic here

    return False
    

year = int(raw_input())
print is_leap(year)
