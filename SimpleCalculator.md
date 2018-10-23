# PythonStuffs
#Learning to code with python - Simple calculator

#Define basic math functions

def add( x, y):
    return x + y

def subract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    return x / y

#Output to user prompting for math function

print("Select operation.")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")

choice = input("Enter choice(1/2/3/4):")

#Output prompting for numbers one and two

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

#Return values of selected numerals

if choice == '1':
    print(num1, "+", num2, "=", add(num1, num2))
elif choice == '2':
    print(num1, "-", num2, "=", subtract(num1, num2))
elif choice == '3':
    print(num1, "*", num2, "=", multiply(num1, num2))
elif choice == '4':
    print(num1, "/", num2, "=", divide(num1, num2))
else:
    print("nonononono")
