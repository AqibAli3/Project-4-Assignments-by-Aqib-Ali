# [*05 Riangle Perimeter*](https://colab.research.google.com/drive/1pBmMJ81MIpXnT3Y1z5LbyWnS4Bo-tWCC?usp=sharing)
## Problem Statement

Prompt the user to enter the lengths of each side of a triangle and then calculate and print the perimeter of the triangle (the sum of all of the side lengths).

Here's a sample run of the program (user input is in bold italics):

What is the length of side 1? 3 

What is the length of side 2? 4 

What is the length of side 3? 5.5 

The perimeter of the triangle is 12.5

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
    side1 = float(input("What is the length of side 1? "))
    side2 = float(input("What is the length of side 2? "))
    side3 = float(input("What is the length of side 3? "))
    perimeter = side1 + side2 + side3
    print("The perimeter of the triangle is " + str(perimeter))

if __name__ == '__main__':
    main()

```

https://colab.research.google.com/drive/1pBmMJ81MIpXnT3Y1z5LbyWnS4Bo-tWCC?usp=sharing


