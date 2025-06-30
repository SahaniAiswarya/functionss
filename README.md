def hi():
    print("hello students")
hi()


def summate(a,b):
    print("sum of two numbers:",a+b)
a=int(input("enter the value of a"))
b=int(input("enter the value of b"))
summate(a,b)

def summate(x,y):
    print("sum of two numbers:",x+y)
a=int(input("enter the value of a"))
b=int(input("enter the value of b"))
summate(a,b)

def summate(x,y):
    return x+y
a=int(input("enter the value of a"))
b=int(input("enter the value of b"))
result=summate(a,b)
print(result)

def summate(x,y):
    print("sum of two numbers:",x+y)
c=int(input("enter the value of c"))
d=int(input("enter the value of d"))
summate(c,d)

def power(base,expo=2):
    return base**expo
num=int(input("enter number"))
print(power(num))

def power(base,expo=2):
    return base**expo
num=int(input("enter number"))
print(power(num))
print(power(num,3))

def power(base,expo=3):
    return base**expo
num=int(input("enter number"))
print(power(num))
print(power(num,3))

def operate(a,b):
    return a+b,a-b,a*b
a=int(input("enter a value:"))
b=int(input("enter b value:"))
sum,diff,prod=operate(a,b)
print("sum",sum)
print("sub",diff)
print("mul",prod)

#anonumous function lambda
#lambda var operation
num=int(input("enter the number"))
square=lambda num:num*num
print(square(num))

#anonumous function lambda
#lambda var operation
a=int(input("enter the a number"))
b=int(input("enter the b number"))
square=lambda a,b:a*b
print(square(a,b))

#nested function
def hi():
    def hello():
        print("inner function")
    print("outer function")
    hello()
hi()

#nested function
def operation(a,b):
    def add():
        return a+b
    def sub():
        return a-b
    print("addition",add())
    print("subtraction",sub())
a=int(input("enter a value"))
b=int(input("enter b value"))
operation(a,b)

