## Problem Statement

We've written a helper function for you called greet(name) which takes as input a string name and prints a greeting. Write some code in main() to get the user's name and then greet them, being sure to call the greet(name) helper function.

Here's a sample run of the program (user input in bold italics):

What's your name? Sophia

Greetings Sophia!

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
def greet(name):
    """
    Returns a greeting message for the given name.
    """
    return "Greetings " + name + "!"

def main():
    """
    Prompts the user for their name and greets them using the helper function.
    """
    name = input("What's your name? ")  # Get the user's name
    print(greet(name))  # Print the greeting from greet()

if __name__ == '__main__':
    main()

```
## https://colab.research.google.com/drive/1jZ_b2ascXLNaT5-omxbB-xVUX0gaTkK5?authuser=4#scrollTo=H9HXpfj5HeWz&line=17&uniqifier=1
