## Problem Statement

Write a program which asks the user how tall they are and prints whether or not they're taller than a pre-specified minimum height.

In amusement parks (ah, the good old pre-pandemic days...), rollercoasters frequently have minimum height requirements for safety reasons. Assume for now that the minimum height is 50 of whatever height unit you'd like

Here's two sample runs (user input is in bold italics):

How tall are you? 100 

You're tall enough to ride!

How tall are you? 10 

You're not tall enough to ride, but maybe next year!

(For an extra challenge, write code which will repeatedly ask a user how tall they are and tell them whether or not they're tall enough to ride, until the user doesn't enter a height at all, in which case the program stops. Curious about how to do this? See the function tall_enough_extension() in the solution code!)

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
MINIMUM_HEIGHT = 50  # arbitrary units :)

def tall_enough_extension():
    while True:
        user_input = input("How tall are you? (Enter nothing to stop) ")
        if user_input == "":  # Stop the loop when no input is provided
            print("Goodbye!")
            break
        try:
            height = float(user_input)
            if height >= MINIMUM_HEIGHT:
                print("You're tall enough to ride!")
            else:
                print("You're not tall enough to ride, but maybe next year!")
        except ValueError:  # Handle invalid inputs that aren't numbers
            print("Please enter a valid number for your height.")

# No need to edit code beyond this point
if __name__ == '__main__':
    tall_enough_extension()
```
https://colab.research.google.com/drive/1mjN5zpUvSNdmfU6dwhLKso8FYV6W3Jqu?authuser=4#scrollTo=_m8FeNDsvmeX&line=12&uniqifier=1



