## Problem Statement

Fill out print_multiple(message, repeats), which takes as parameters a string message to print, and an integer repeats number of times to print message. We've written the main() function for you, which prompts the user for a message and a number of repeats.

Here's a sample run of the program (user input is in blue):

Please type a message: Hello! 
Enter a number of times to repeat your message: 6 
Hello! 
Hello! 
Hello! 
Hello! 
Hello! 
Hello!

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
def print_multiple(message: str, repeats: int):
    """
    Prints the given message a specified number of times.
    """
    for i in range(repeats):  # Loop through the number of repeats
        print(message)  # Print the message

# No need to edit code beyond this point
def main():
    """
    Main function to get user input and print the message multiple times.
    """
    message = input("Please type a message: ")  # Prompt user for a message
    repeats = int(input("Enter a number of times to repeat your message: "))  # Prompt user for number of repeats
    print_multiple(message, repeats)  # Call the function to print the message

if __name__ == '__main__':
    main()
```
## https://colab.research.google.com/drive/10FuvcHQ51NcXx-FgRNBX4yYZ6z_wRGbx?authuser=4#scrollTo=lT9NlUOttoyQ&line=19&uniqifier=1
