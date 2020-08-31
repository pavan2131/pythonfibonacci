# pythonfibonacci
# printing fibonacci num upto user input range
y = int(input())
a = 0
b = 1
while int(y)>0 :
    print(a)
    a,b = b,a+b
    y = y-1
