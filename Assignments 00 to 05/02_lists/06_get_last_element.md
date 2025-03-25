## Problem Statement

Fill out the function get_last_element(lst) which takes in a list lst as a parameter and prints the last element in the list. The list is guaranteed to be non-empty, but there are no guarantees on its length.

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

```
def get_last_element(lst):
    print(lst[-1])  # Directly prints the last element of the list using negative indexing

def get_lst():
    lst = []
    while True:
        elem = input("Please enter an element of the list or press enter to stop: ")
        if elem == "":
            break
        lst.append(elem)
    return lst

def main():
    lst = get_lst()
    get_last_element(lst)

if __name__ == '__main__':
    main()
```

https://colab.research.google.com/drive/14vpKAsi1uIUb4ROCUols6HuE78eugFpH?authuser=4#scrollTo=TcnZMPCc5kSG&line=19&uniqifier=1
