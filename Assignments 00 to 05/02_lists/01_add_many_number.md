## Problem Statement

Write a function that takes a list of numbers and returns the sum of those numbers.

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
def add_many_numbers(numbers)-> int:
    """
    Takes in a list of numbers and returns the sum of those numbers.
    """

    total_so_far: int = 0
    for number in numbers:
        total_so_far += number

    return total_so_far

# There is no need to edit code beyond this point

def main():
    numbers: list[int] = [1, 2, 3, 4, 5]  # Make a list of numbers
    sum_of_numbers: int = add_many_numbers(numbers)  # Find the sum of the list
    print(sum_of_numbers)  # Print out the sum above
    

if __name__ == '__main__':
    main()
```
(https://colab.research.google.com/drive/1GVx63FnzO_wWqED7rx_bo9IqrH593XBc?authuser=4#scrollTo=QCK_L5qHy86j&line=1&uniqifier=1)
