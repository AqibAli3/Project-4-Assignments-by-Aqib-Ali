# [*01 Add Two Numbers*](https://colab.research.google.com/drive/1yEIxcerjDKaISA0F_SSquDkLYIfcqYm-?authuser=4#scrollTo=Qt26auvVo8JR)


## Problem Statement

Write a Python program that takes two integer inputs from the user and calculates their sum. The program should perform the following tasks:

1. Prompt the user to enter the first number.

2. Read the input and convert it to an integer.

3. Prompt the user to enter the second number.

4. Read the input and convert it to an integer.

5. Calculate the sum of the two numbers.

6. Print the total sum with an appropriate message.

The provided solution demonstrates a working implementation of this problem, where the main() function guides the user through the process of entering two numbers and displays their sum.

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

(https://colab.research.google.com/drive/1yEIxcerjDKaISA0F_SSquDkLYIfcqYm-?authuser=4#scrollTo=Qt26auvVo8JR)

# This program calculates the sum of two numbers.

def main():
    print("This program will calculate the sum of two numbers.")

    num1 = input("Enter the first number: ")
    num1 = int(num1)

    num2 = input("Enter the second number: ")
    num2 = int(num2)

    total = num1 + num2

    print("The sum of the two numbers is: " + str(total) + ".")


if __name__ == '__main__':
    main()

