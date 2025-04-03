## Problem Statement

Write a function called print_ones_digit , which takes as a parameter an integer num and prints its ones digit. The modulo (remainder) operator, %, should be helpful to you here. Call your function from main()!

Here's a sample run (user input is in blue):

Enter a number: 42
The ones digit is 2

## Starter Code

```bash
def main():
    print("Delete this line and write your code here! :)")


# This provided line is required at the end of
# Python file to call the main() function.
if __name__ == '__main__':
    main()
```

## Solution
```bash
def print_ones_digit(num):
    """
    Prints the ones digit of the given integer.
    """
    print("The ones digit is", num % 10)  # Get the ones digit using the modulo operator

def main():
    """
    Main function to take user input and call print_ones_digit.
    """
    num = int(input("Enter a number: "))  # Prompt user to enter a number
    print_ones_digit(num)  # Call the helper function with the input number

# Required boilerplate to run the program
if __name__ == '__main__':
    main()
```
## https://colab.research.google.com/drive/1eP5DBfB-QawNJAf78FegaF8MZIbuvhR1?authuser=4#scrollTo=wA3a3zH8ugPk&line=17&uniqifier=1
