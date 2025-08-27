# Calculator-Python-
# A simple Python Calculator that performs basic arithmetic operations like addition, subtraction, multiplication, and division using user input. It helps practice conditional statements, functions, and input handling in Python.
try:
    a = int(input("Enter first number: "))
    b = int(input("Enter second number: "))
    print("What kind of operation do you want to perform?\nPress + for addition\nPress - for subtraction\nPress * for multiplication\nPress / for division")
    o = input("Enter Operation: ")
    match o:
        case "+":
            print(f"The result of {a} + {b} is: {a + b}")
    
        case "-":
            print(f"The result of {a} - {b} is: {a - b}")
    
        case "*":
            print(f"The result of {a} * {b} is: {a * b}")
    
        case "/":
            print(f"The result of {a} / {b} is: {a / b}") 
except Exception as e:
    print("Enter a valid value of a and b")
