# [01 Dicesimulator](https://colab.research.google.com/drive/1cn2wgds3FaoVcmfq56tIdHxRRCZw-SK_?authuser=4#scrollTo=muBOO6tWJDM3&line=21&uniqifier=1)

# Problem Statement

Simulate rolling two dice, three times.  Prints the results of each die roll.  This program is used to show how variable scope works.

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
[import random

NUM_SIDES = 6

def roll_dice():
    die1 = random.randint(1, NUM_SIDES)
    die2 = random.randint(1, NUM_SIDES)
    total = die1 + die2
    print("Total of two dice:", total)

def main():
    die1 = 10
    print("die1 in main() starts as: " + str(die1))
    roll_dice()
    roll_dice()
    roll_dice()
    print("die1 in main() is: " + str(die1))

if __name__ == '__main__':
    main()
    ](https://colab.research.google.com/drive/1cn2wgds3FaoVcmfq56tIdHxRRCZw-SK_?authuser=4#scrollTo=muBOO6tWJDM3&line=1&uniqifier=1)
