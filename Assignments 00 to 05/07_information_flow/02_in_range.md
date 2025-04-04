## Problem Statement

Implement the following function which takes in 3 integers as parameters:

def in_range(n, low, high)
  """
  Returns True if n is between low and high, inclusive. 
  high is guaranteed to be greater than low.
  """

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
def in_range(n, low, high):
    """
    Returns True if n is between low and high, inclusive.
    high is guaranteed to be greater than low.
    """
    if n >= low and n <= high:  
        return True
    return False  

def main():
    n = int(input("Enter a number: "))  
    low = int(input("Enter the lower bound: "))  
    high = int(input("Enter the upper bound: "))  
    print(in_range(n, low, high))  

if __name__ == '__main__':
    main()

```
## https://colab.research.google.com/drive/1bHdhIlVhdMeo9K7JXOmuMF6VCI5vv7lY?authuser=4#scrollTo=Oky726s6IC6I&line=9&uniqifier=1
