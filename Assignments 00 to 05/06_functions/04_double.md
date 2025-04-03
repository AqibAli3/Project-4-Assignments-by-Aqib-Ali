## Problem Statement

Fill out the double(num) function to return the result of multiplying num by 2. We've written a main() function for you which asks the user for a number, calls your code for double(num) , and prints the result.

Here's a sample run of the program (user input in bold italics):

Enter a number: 2 
Double that is 4

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
def double(num: int):
    """
    Function to double the given number.
    """
    return num * 2

def main():
    """
    Main function to ask the user for a number, double it,
    and print the result.
    """
    num = int(input("Enter a number: "))  # Prompt user input
    num_times_2 = double(num)            # Call double() function
    print("Double that is", num_times_2) # Print the result

if __name__ == '__main__':
    main()

```
## https://colab.research.google.com/drive/1Ob9loikW_zPGjx4IlcXWqsTho9vvX3V-?authuser=4#scrollTo=nKBuUwtUr04V&line=20&uniqifier=1
