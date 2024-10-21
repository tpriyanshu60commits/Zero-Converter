# Zero-Converter

def negative(n):
    while n <=0:
        print(n)
        n +=1
        
def positive (n):
    while n>0:
        print(n-1)
        n -=1
        
def print_number(n):
    if n<0:
        negative(n)
    else:
        positive(n)
        
n = int(input("enter the number - "))
print_number(n)
        
