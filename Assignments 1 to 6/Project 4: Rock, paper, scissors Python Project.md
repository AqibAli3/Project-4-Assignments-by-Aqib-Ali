# Project 4: Rock, paper, scissors Python Project

```
import random

def rock_paper_scissors():
    print("Welcome to Rock, Paper, Scissors!")
    print("Type your choice: rock, paper, or scissors. Type 'quit' to exit the game.")
    
    choices = ["rock", "paper", "scissors"]
    user_score = 0
    computer_score = 0

    while True:
        # Get the user's choice
        user_choice = input("\nYour choice: ").strip().lower()

        # Exit the game if the user types 'quit'
        if user_choice == "quit":
            print(f"\nFinal Scores: You: {user_score}, Computer: {computer_score}")
            print("Thanks for playing!")
            break

        # Validate user's choice
        if user_choice not in choices:
            print("Invalid choice. Please choose rock, paper, or scissors.")
            continue

        # Computer's random choice
        computer_choice = random.choice(choices)
        print(f"Computer chose: {computer_choice}")

        # Determine the winner
        if user_choice == computer_choice:
            print("It's a tie!")
        elif (user_choice == "rock" and computer_choice == "scissors") or \
             (user_choice == "paper" and computer_choice == "rock") or \
             (user_choice == "scissors" and computer_choice == "paper"):
            print("You win this round!")
            user_score += 1
        else:
            print("Computer wins this round!")
            computer_score += 1

        # Display scores
        print(f"Current Scores: You: {user_score}, Computer: {computer_score}")

# Call the function
rock_paper_scissors()

```
### https://colab.research.google.com/drive/1EoA7rGsX3hMkKoe1uw2haCQP4kWWtUZJ?authuser=4#scrollTo=guo00Z7Vok7F&line=18&uniqifier=1
