

## Problem Statement

Converts feet to inches. Feet is an American unit of measurement. There are 12 inches per foot. Foot is the singular, and feet is the plural.

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
```
INCHES_IN_FOOT = 12

def main():
    feet = float(input("Enter number of feet: "))
    inches = feet * INCHES_IN_FOOT
    print("That is", inches, "inches!")

if __name__ == '__main__':
    main()

```
https://colab.research.google.com/drive/1xj5yQ4D2ajYFmAS3hTYCYZ-EwJC2AkWd?authuser=4#scrollTo=7HPbSacNP1Pt&line=10&uniqifier=1
