## solution

```bash
import random

NUM_ROUNDS = 5  # Number of rounds the game will play

def main():
    print("Welcome to the High-Low Game!")
    print("--------------------------------")
    score = 0  # Initialize the player's score

    for round_num in range(1, NUM_ROUNDS + 1):
        print(f"Round {round_num}")
        user_number = random.randint(1, 100)  # Generate the user's number
        computer_number = random.randint(1, 100)  # Generate the computer's number

        print(f"Your number is {user_number}")
        user_guess = input("Do you think your number is higher or lower than the computer's?: ").strip().lower()

        # Ensure valid input
        while user_guess not in ["higher", "lower"]:
            user_guess = input("Please enter either higher or lower: ").strip().lower()

        # Determine if the user's guess is correct
        if (user_guess == "higher" and user_number > computer_number) or \
           (user_guess == "lower" and user_number < computer_number):
            print(f"You were right! The computer's number was {computer_number}")
            score += 1  # Increment the score for a correct guess
        else:
            print(f"Aww, that's incorrect. The computer's number was {computer_number}")

        print(f"Your score is now {score}\n")

    # Add conditional messages at the end
    print("Thanks for playing!")
    if score == NUM_ROUNDS:
        print("Wow! You played perfectly!")
    elif score >= NUM_ROUNDS // 2:
        print("Good job, you played really well!")
    else:
        print("Better luck next time!")

if __name__ == '__main__':
    main()

```

## https://colab.research.google.com/drive/1f0ox5TlbFYbuOQ0do6KigBRV_Ci6uvvX?authuser=4#scrollTo=pA1EyAVnSN2a&line=43&uniqifier=1
