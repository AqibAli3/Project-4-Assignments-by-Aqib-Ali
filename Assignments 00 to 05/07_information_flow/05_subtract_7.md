## Problem Statement

Fill out the subtract_seven helper function to subtract 7 from num, and fill out the main() method to call the subtract_seven helper function! If you're stuck, revisit the add_five example from lecture.

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
def subtract_seven(num):
    """
    Subtracts 7 from the given number.
    """
    return num - 7 

def main():
    """
    Calls the subtract_seven function and prints the result.
    """
    num = 7  
    num = subtract_seven(num)  
    print("This should be zero:", num)  

if __name__ == '__main__':
    main()
```
## https://colab.research.google.com/drive/1XLvw6IKUJ9C_fffcVoGhGVKUbE9VVoEN?authuser=4#scrollTo=uO16H3mzIsK7&line=14&uniqifier=1
