# CODSOFT_Task_2
Number_1 = float(input("Enter the frist number: ")) #Enter the frist number here
Number_2 = float(input("Enter the second number: ")) #Enter the second number here
operation = input('(Adding (+),\n Substract (-)\n Multiply (*),\n Divide (/),\nEnter the operation symbole  : ')# Choose the operation using symbole

if operation == '+' :  # Addition of two number 
    Add = Number_1 + Number_2
    print(Add)

if operation == '-':   # Substraction of two number
    Sub = Number_1 - Number_2
    print(Sub)

if operation == '/':   # Division of two number 
    Div = Number_1/Number_2
    print(Div)

if operation == '*':   # Multiplication of two number 
    Mul = Number_1 * Number_2
    print(Mul)
