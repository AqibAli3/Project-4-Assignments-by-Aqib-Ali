# Mars Weight Solution

```bash
MARS_MULTIPLE = 0.378  # Mars gravity constant compared to Earth's

def main():
    # Prompt the user for their weight on Earth
    earth_weight = float(input("Enter a weight on Earth: "))

    # Calculate weight on Mars
    mars_weight = round(earth_weight * MARS_MULTIPLE, 2)

    # Print the equivalent weight on Mars
    print(f"The equivalent on Mars: {mars_weight}")

if __name__ == "__main__":
    main()
```

# Planetary Weights Solution
```bash
def main():
    planet_gravity = {
        "Mercury": 0.376,
        "Venus": 0.889,
        "Mars": 0.378,
        "Jupiter": 2.36,
        "Saturn": 1.081,
        "Uranus": 0.815,
        "Neptune": 1.14
    }
    
    earth_weight = float(input("Enter a weight on Earth: "))  # Prompt user for weight
    planet_name = input("Enter a planet: ")  # Prompt user for planet name

    # Calculate and print the equivalent weight on the selected planet
    if planet_name in planet_gravity:
        planet_weight = round(earth_weight * planet_gravity[planet_name], 2)
        print(f"The equivalent weight on {planet_name}: {planet_weight}")
    else:
        print("Invalid planet name.")

if __name__ == "__main__":
    main()
```
## https://colab.research.google.com/drive/1l8DHEoBaaB7hvBoqI38_6uO1BUCUHj0n?authuser=4#scrollTo=Ly1j0E20Rt--&line=5&uniqifier=1
