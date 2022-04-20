# Basic-Calculator-using-Python
# Q1. Basic Calculator using Python
# Given below is code for Basic Calculator

print("Select operation to perform: ")
print("1. ADD")
print("2. SUBTRACT")
print("3. MULTIPLY")
print("4. DIVIDE")

operation = input(“Please Enter Valid Input: “) 
#Addition
if operation == "1":
    num1 = input("Enter First Number: ")
    num2 = input("Enter Second Number: ") 
    print("The Sum is = " + str(int(num1) + int(num2)))
#Subtraction
elif operation == 2:
    num1 = input("Enter First Number: ")
    num2 = input("Enter Second Number: ")
    print("The Subtraction is = " + str(int(num1) - int(num2)))
#Division
elif operation == 3:
    num1 = input("Enter First Number: ")
    num2 = input("Enter Second Number: ")
    print("The Division is = " + str(int(num1) / int(num2)))
#Multiply
elif operation == 4:
    num1 = input("Enter First Number: ")
    num2 = input("Enter Second Number: ")
    print("The Multiple is = " + str(int(num1) * int(num2)))
else: print("Invalid Entry")

