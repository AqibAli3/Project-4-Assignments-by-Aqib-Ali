## Problem Statement

Implement the helper function make_sentence(word, part_of_speech) which will take a string word and an integer part_of_speech as parameters and, depending on the part of speech, place the word into one of three sentence templates (or one from your imagination!):

If part_of_speech is 0, we will assume the word is a noun and use the template: "I am excited to add this ____ to my vast collection of them!"

If part_of_speech is 1, we will assume the word is a verb use the template: "It's so nice outside today it makes me want to ____!"

If part_of_speech is 2, we will assume the word is an adjective and use the template: "Looking out my window, the sky is big and ____!" make_sentence(word, part_of_speech) should not return anything, just print the correct sentence with the word filled in the blank.

Here's a sample run of the program (user input is in blue):

Please type a noun, verb, or adjective: groovy 
Is this a noun, verb, or adjective?
Type 0 for noun, 1 for verb, 2 for adjective: 2 
Looking out my window, the sky is big and groovy!

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
def make_sentence(word, part_of_speech):
    """
    Constructs a sentence using the given word and part of speech.
    """
    if part_of_speech == 0:
        # Noun template
        print("I am excited to add this " + word + " to my vast collection of them!")
    elif part_of_speech == 1:
        # Verb template
        print("It's so nice outside today it makes me want to " + word + "!")
    elif part_of_speech == 2:
        # Adjective template
        print("Looking out my window, the sky is big and " + word + "!")
    else:
        # Invalid input for part of speech
        print("Part of speech must be 0, 1, or 2! Can't make a sentence.")

# No need to edit code beyond this point
def main():
    """
    Main function for user interaction and processing.
    """
    word = input("Please type a noun, verb, or adjective: ")  # Prompt user for a word
    print("Is this a noun, verb, or adjective?")
    part_of_speech = int(input("Type 0 for noun, 1 for verb, 2 for adjective: "))  # Prompt user for part of speech
    make_sentence(word, part_of_speech)  # Call helper function with inputs

# Entry point of the program
if __name__ == '__main__':
    main()


```
## https://colab.research.google.com/drive/1gptRKaYepZBcxd3HKvPQvoqB77ESc0qG?authuser=4#scrollTo=Xj9Ves4Qty_-&line=31&uniqifier=1
