# Mad libs Python Project
## solution 

```bash
def mad_libs():
    print("Welcome to the Mad Libs game!")

    # Get user inputs
    noun = input("Enter a noun: ")
    verb = input("Enter a verb: ")
    adjective = input("Enter an adjective: ")
    place = input("Enter a place: ")

    # Create the story using the user inputs
    story = f"Once upon a time, in the magical land of {place}, there was a {adjective} {noun}. Every day, it loved to {verb} and explore the world around it!"

    # Print the completed story
    print("\nHere is your Mad Libs story:")
    print(story)

# Call the function
mad_libs()
```
