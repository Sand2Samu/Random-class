import streamlit as st

# Function to perform the calculator operations
def calculate():
    st.title("Simple Calculator")

    # Create input fields for numbers
    num1 = st.number_input("Enter the first number", value=0)
    num2 = st.number_input("Enter the second number", value=0)

    # Dropdown menu for selecting the operation
    operation = st.selectbox("Select an operation", ["Add", "Subtract", "Multiply", "Divide"])

    # Perform the operation based on the user selection
    if operation == "Add":
        result = num1 + num2
    elif operation == "Subtract":
        result = num1 - num2
    elif operation == "Multiply":
        result = num1 * num2
    elif operation == "Divide":
        if num2 != 0:
            result = num1 / num2
        else:
            result = "Error: Division by zero"

    # Display the result
    st.write(f"**Result:** {result}")

# Call the function to run the calculator
if __name__ == "__main__":
    calculate()
