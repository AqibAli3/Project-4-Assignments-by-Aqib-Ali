## Problem Statement

Guess My Number

I am thinking of a number between 0 and 99...
Enter a guess: 50
Your guess is too high

Enter a new number: 25
Your guess is too low

Enter a new number: 40
Your guess is too low

Enter a new number: 45
Your guess is too low

Enter a new number: 48
Congrats! The number was: 48

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
import random

def main():
    secret_number = random.randint(1, 99)
    print("I am thinking of a number between 1 and 99...")
    
    guess = int(input("Enter a guess: "))
    
    while guess != secret_number:
        if guess < secret_number:
            print("Your guess is too low")
        else:
            print("Your guess is too high")
            
        print()
        guess = int(input("Enter a new guess: "))
    
    print("Congrats! The number was: " + str(secret_number))

if __name__ == '__main__':
    main()
```
## https://colab.research.google.com/drive/1YzqIcCsxhIjPsO_gEw7aeqmtpHeMvzXM?authuser=4#scrollTo=VErFJEQAQM8w&line=22&uniqifier=1
