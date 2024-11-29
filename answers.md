# Simple Calculator Program

# Function to perform the selected operation
def calculate(num1, num2, operation):
    if operation == '+':
        return num1 + num2
    elif operation == '-':
        return num1 - num2
    elif operation == '*':
        return num1 * num2
    elif operation == '/':
        return num1 / num2
    else:
        return "Invalid operation"

# Main program
def main():
    # Get input from the user
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
    operation = input("Enter the operation (+, -, *, /): ")

    # Perform the calculation and print the result
    result = calculate(num1, num2, operation)
    print(f"{num1} {operation} {num2} = {result}")

# Run the main program
if __name__ == "__main__":
    main()
