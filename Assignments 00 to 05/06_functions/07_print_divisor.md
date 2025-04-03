## Problem Statement

Write the helper function print_divisors(num), which takes in a number and prints all of its divisors (all the numbers from 1 to num inclusive that num can be cleanly divided by (there is no remainder to the division). Don't forget to call your function in main()!

Here's a sample run (user input is in blue):

Enter a number: 12 
Here are the divisors of 12 
1 
2 
3 
4 
6 
12

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
def print_divisors(num: int):
    """
    Prints all divisors of the given number.
    """
    print("Here are the divisors of", num)
    for i in range(1, num + 1):  # Loop through numbers from 1 to num
        if num % i == 0:  # Check if i is a divisor of num
            print(i)  # Print the divisor

def main():
    """
    Main function to get user input and call print_divisors().
    """
    num = int(input("Enter a number: "))  # Prompt the user for a number
    print_divisors(num)  # Call the helper function to print divisors

# Call the main function when the program runs
if __name__ == '__main__':
    main()

```
## https://colab.research.google.com/drive/1eIwa2H7sq1qbVZdQuXdlU-JdT8giwyiy?authuser=4#scrollTo=uJBXjH1_tErL&line=20&uniqifier=1
