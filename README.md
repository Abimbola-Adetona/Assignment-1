# Assignment-1
Write a program that print the first N prime numbers. N should be declared as a variable at the beginning of your code.
num = eval(input('Enter number: '))

N = 0
for i in range(2,num):
    if num%i==0:
       N = 1
if N==1:
    print('Not prime')
else:
    print('Prime')
