# Guess the Number Game Python Project (user)

```bash
# Run this cell in Google Colab to play the Guess the Number Game (User Guesses)!

import random

def guess_number_user():
    print("Welcome to the Guess the Number Game!")
    print("I have chosen a number between 1 and 100. Can you guess it?")

    # Computer generates a random number
    secret_number = random.randint(1, 100)
    guess = None
    attempts = 0

    while guess != secret_number:
        # User inputs their guess
        guess = int(input("Enter your guess: "))
        attempts += 1

        # Provide feedback
        if guess < secret_number:
            print("Your guess is too low.")
        elif guess > secret_number:
            print("Your guess is too high.")
        else:
            print(f"Congratulations! You guessed the correct number: {secret_number}")
            print(f"It took you {attempts} attempts.")

# Call the function
guess_number_user()
```
