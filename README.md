# python

# Simple Calculator

num1 = float(input("First number: "))
num2 = float(input("Second number: "))
op = input("Operation (+, -, *, /): ")

if op == "+":
    print(num1 + num2)
elif op == "-":
    print(num1 - num2)
elif op == "*":
    print(num1 * num2)
elif op == "/":
    if num2 != 0:
        print(num1 / num2)
    else:
        print("Can't divide by zero.")
else:
    print("Invalid operation.")
