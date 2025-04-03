## Problem Statement

Write a function that takes two numbers and finds the average between the two.

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
def average(a: float, b: float):
    """
    Returns the number which is halfway between a and b
    """
    sum = a + b
    return sum / 2

def main():
    # Compute averages for different pairs
    avg_1 = average(0, 10)
    avg_2 = average(8, 10)
    
    # Calculate a final average using previous results
    final = average(avg_1, avg_2)
    
    # Print out the results
    print("avg_1:", avg_1)  # Average of 0 and 10
    print("avg_2:", avg_2)  # Average of 8 and 10
    print("final:", final)  # Final average

# Boilerplate to run the program
if __name__ == '__main__':
    main()

```
## https://colab.research.google.com/drive/1pNcsTi1Xdy5VqQK9Q9z6G0Hq-9ubiYqm?authuser=4#scrollTo=vzSSZqfDlpWF&line=24&uniqifier=1
