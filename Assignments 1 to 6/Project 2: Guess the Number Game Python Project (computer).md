# Guess the Number Game Python Project (Computer)

```bash
import random

def guess_number_computer():
    print("Welcome to the Guess the Number Game!")
    print("Think of a number between 1 and 100, and let the computer guess it!")

    # Setting the range
    low = 1
    high = 100
    feedback = ""

    while feedback != "correct":
        # Computer makes a guess
        guess = random.randint(low, high)
        print(f"Computer guesses: {guess}")
        
        # Prompt for user feedback
        feedback = input("Is the guess too high, too low, or correct? ").strip().lower()

        # Adjust the range based on feedback
        if feedback == "too high":
            high = guess - 1
        elif feedback == "too low":
            low = guess + 1
        elif feedback == "correct":
            print(f"Yay! The computer guessed your number: {guess}")
        else:
            print("Please enter valid feedback ('too high', 'too low', or 'correct').")

# Call the function
guess_number_computer()
```
### https://colab.research.google.com/drive/1BdkmKycBtLD9HSv5-clE__pcyVYmni9F?usp=sharing
