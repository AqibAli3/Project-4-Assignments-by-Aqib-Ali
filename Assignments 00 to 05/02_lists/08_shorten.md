## Problem Statement

Fill out the function shorten(lst) which removes elements from the end of lst, which is a list, and prints each item it removes until lst is MAX_LENGTH items long. If lst is already shorter than MAX_LENGTH you should leave it unchanged. We've written a main() function for you which gets a list and passes it into your function once you run the program. For the autograder to pass you will need MAX_LENGTH to be 3, but feel free to change it around to test your program.

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
MAX_LENGTH = 3  # Set the maximum length for the list

def shorten(lst):
    # Keep removing elements from the end of the list until its length is MAX_LENGTH
    while len(lst) > MAX_LENGTH:
        last_elem = lst.pop()
        print(last_elem)

def get_lst():
    # Prompt the user to enter elements into a list
    lst = []
    elem = input("Please enter an element of the list or press enter to stop: ")
    while elem != "":
        lst.append(elem)
        elem = input("Please enter an element of the list or press enter to stop: ")
    return lst

def main():
    # Generate the list and shorten it based on MAX_LENGTH
    lst = get_lst()
    shorten(lst)

if __name__ == '__main__':
    main()

```
https://colab.research.google.com/drive/11laxkTABRfWrFaM_awyeThXHfYGGUljG?authuser=4#scrollTo=b4dkjPcHGv4u&line=25&uniqifier=1
