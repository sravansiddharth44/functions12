# functions12
using function in functions arthemtic operations 
def cal(a,b):
    def add():
        return a+b
    def sub():
        return a-b
    def mul():
        return a*b
    print("addiion",add())
    print("subtr" ,sub())
    print("mul", mul())
a=int(input("enter any function: "))
b=int(input("enter any function: "))
cal(a,b)
