## Problem Statement

Fill out the get_name() function to return your name as a string! We've written a main() function for you which calls your function to retrieve your name and then prints it in a greeting.

Here's a sample run of the program where the name we've decided to return is Sophia (the autograder expects the returned name to be Sophia):

Howdy Sophia ! 🤠

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
def get_name():
    """
    This function returns the name 'Sophia' as required.
    """
    return "Sophia"

def main():
    """
    Main function retrieves the name and prints a greeting.
    """
    name = get_name()  # Fetch the name from get_name function
    print("Howdy", name, "! 🤠")  # Print the personalized greeting

if __name__ == '__main__':
    main()

```
## https://colab.research.google.com/drive/1FB2ZZj4abpJmP2jBm0LBAoBfupCmkd-J?authuser=4#scrollTo=K7yFLiNesORr&line=6&uniqifier=1
