# Index Game Solution
```bash
def access_element(lst, index):
    """
    Accesses an element in the list at the given index.
    """
    if 0 <= index < len(lst):
        return lst[index]
    return "Index out of range"

def modify_element(lst, index, new_value):
    """
    Modifies an element in the list at the given index.
    """
    if 0 <= index < len(lst):
        lst[index] = new_value
        return "List updated successfully"
    return "Index out of range"

def slice_list(lst, start, end):
    """
    Slices the list from start index to end index (exclusive).
    """
    if 0 <= start < len(lst) and 0 <= end <= len(lst) and start <= end:
        return lst[start:end]
    return "Invalid range"

def main():
    # Initialize a list with mixed elements
    my_list = [10, "hello", 3.14, "world", 100]

    while True:
        print("\nCurrent list:", my_list)
        print("Choose an operation:")
        print("1. Access an element")
        print("2. Modify an element")
        print("3. Slice the list")
        print("4. Exit")

        choice = input("Enter your choice (1-4): ")

        if choice == '1':  # Access an element
            index = int(input("Enter the index to access: "))
            print("Result:", access_element(my_list, index))

        elif choice == '2':  # Modify an element
            index = int(input("Enter the index to modify: "))
            new_value = input("Enter the new value: ")
            print("Result:", modify_element(my_list, index, new_value))

        elif choice == '3':  # Slice the list
            start = int(input("Enter the start index: "))
            end = int(input("Enter the end index: "))
            print("Result:", slice_list(my_list, start, end))

        elif choice == '4':  # Exit the game
            print("Exiting the game. Goodbye!")
            break

        else:
            print("Invalid choice. Please try again.")

if __name__ == '__main__':
    main()


```

# List Practice Solution
```bash
def main():
    # Create a list called `fruit_list` that contains the following fruits:
    fruit_list = ['apple', 'banana', 'orange', 'grape', 'pineapple']

    # Print the length of the list
    print("Length of the fruit list:", len(fruit_list))

    # Add 'mango' at the end of the list
    fruit_list.append('mango')

    # Print the updated list
    print("Updated fruit list:", fruit_list)

if __name__ == '__main__':
    main()
```
### https://colab.research.google.com/drive/1ELfJYm_ly_HMNVNy-9lyF-ZAsk2gGo-W?usp=sharing
