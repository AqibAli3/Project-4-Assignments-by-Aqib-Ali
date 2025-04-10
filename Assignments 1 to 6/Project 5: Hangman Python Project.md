# Project 5: Hangman Python Project

```bash
import random

def hangman():
    print("Welcome to Hangman!")

    # List of possible words
    words = ['python', 'hangman', 'programming', 'coding', 'developer']
    secret_word = random.choice(words)
    guessed_letters = set()
    attempts = 6  # Maximum wrong guesses allowed

    print("\nThe word has", len(secret_word), "letters.")
    print("_ " * len(secret_word))  # Display blanks for the secret word

    while attempts > 0:
        # Get user's guess
        guess = input("\nGuess a letter: ").lower()

        # Validate input
        if len(guess) != 1 or not guess.isalpha():
            print("Please enter a single alphabetic character.")
            continue

        # Check if the letter is in the word
        if guess in secret_word:
            guessed_letters.add(guess)
            print("Good guess!")
        else:
            attempts -= 1
            print(f"Wrong guess! You have {attempts} attempts remaining.")

        # Display the current state of the word
        current_state = ''.join([letter if letter in guessed_letters else '_ ' for letter in secret_word])
        print("Current word:", current_state)

        # Check if the user has guessed all the letters
        if set(secret_word) == guessed_letters:
            print("\nCongratulations! You guessed the word:", secret_word)
            break
    else:
        print("\nGame over! The word was:", secret_word)

# Call the function
hangman()
```
### https://colab.research.google.com/drive/1hfxrD_Ss4AOm_zjIR8oabTG7PFTFwb8l?authuser=4#scrollTo=3m5w8QHdrSXY&line=1&uniqifier=1
