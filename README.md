# Calculator
This is the script for a calculator!
-------------
print("Welcome to my calculator!")
operation = int(input("Press 1 to Add, Press 2 to Subtract, Press 3 to Multiply, Press 4 to Divide"))

num1 = (float)(input("Enter the first number:"))
num2 = (float)(input("Enter the second number:"))
print ("The result is:")

if (operation == 1):
    print(add(num1, num2))
elif(operation == 2):
    print(subtract(num1, num2))
elif(operation == 3):
    print(multiply(num1, num2))
else:
    print(divide(num1, num2))
