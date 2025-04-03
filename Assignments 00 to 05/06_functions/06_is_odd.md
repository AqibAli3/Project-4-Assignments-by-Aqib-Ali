## Problem Statement

10 even
11 odd
12 even
13 odd
14 even
15 odd
16 even
17 odd
18 even
19 odd

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
def main():
    for i in range(10, 20):  # Loop through numbers from 10 to 19
        if is_odd(i):  # Check if the current number is odd
            print(i, "odd")  # Print the number and "odd"
        else:
            print(i, "even")  # Print the number and "even"
            
def is_odd(value: int):
    """
    Checks to see if a value is odd. Returns True if it is, False otherwise.
    """
    return value % 2 == 1  # Returns True if the value is not divisible by 2

# Call the main function when the program runs
if __name__ == '__main__':
    main()

```
## https://colab.research.google.com/drive/1ctBwdpV7_SWJBcjq2_QNQ-TaglKJyuBd?authuser=4#scrollTo=lFRrkvvgsvMz&line=17&uniqifier=1
