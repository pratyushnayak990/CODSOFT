def calculator():
    num1 = input("Enter first number: ")
    num2 = input("Enter second number: ")

    print("Enter '+' to add two numbers")
    print("Enter '-' to subtract two numbers")
    print("Enter '*' to multiply two numbers")
    print("Enter '/' to divide two numbers")
    print("Enter 'quit' to end the program")

    user_input = input(": ")

    if user_input == "quit":
        print("Exiting the program.")
        return

    if user_input in ("+", "-", "*", "/"):
        num1 = float(num1)
        num2 = float(num2)

        if user_input == "+":
            result = num1 + num2
            print(f"{num1} + {num2} = {result}")

        elif user_input == "-":
            result = num1 - num2
            print(f"{num1} - {num2} = {result}")

        elif user_input == "*":
            result = num1 * num2
            print(f"{num1} * {num2} = {result}")

        elif user_input == "/":
            if num2 != 0:
                result = num1 / num2
                print(f"{num1} / {num2} = {result}")
            else:
                print("Error! Division by zero.")
    else:
        print("Invalid operation.")

# Call the calculator function
calculator()
