## Problem Statement

Ask the user for two numbers, one at a time, and then print the result of dividing the first number by the second and also the remainder of the division. 

Here's a sample run of the program (user input is in bold italics):

Please enter an integer to be divided: 5

Please enter an integer to divide by: 3

The result of this division is 1 with a remainder of 2

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


```
def main():
    dividend = int(input("Please enter an integer to be divided: "))
    divisor = int(input("Please enter an integer to divide by: "))

    quotient = dividend // divisor
    remainder = dividend % divisor
    
    print("The result of this division is " + str(quotient) + " with a remainder of " + str(remainder))

if __name__ == '__main__':
    main()
```

https://colab.research.google.com/drive/1GJ_5OOn3iYgZOp_1rsHBooayM2Re3xmT#scrollTo=rsxtwRX7siE6&line=12&uniqifier=1
