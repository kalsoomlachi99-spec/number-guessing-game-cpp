# Number Guessing Game (C++)

A simple console-based Number Guessing Game written in C++.

## Description

The program generates a random number between 1 and 100. The player tries to guess the number within 10 attempts.

After each guess, the game provides a hint:

- "Too high!" if the guess is greater than the secret number.
- "Too low!" if the guess is smaller than the secret number.

The game ends when:
- The player guesses the correct number, or
- The player uses all 10 attempts.

## Features

- Random number generation
- Maximum of 10 attempts
- Hints after each guess
- Tracks the number of attempts
- Winning and losing messages
- Uses the current system time to generate different random numbers each game

## Concepts Used

- Variables
- User Input and Output (`cin`, `cout`)
- `while` loops
- `if-else` statements
- Boolean variables
- Random number generation (`rand()`)
- Seeding with `srand(time(0))`

## How to Compile

Using g++:

```bash
g++ number_guessing_game.cpp -o game
```

## How to Run

Windows:

```bash
game.exe
```

Linux/macOS:

```bash
./game
```

## Example

```text
Guess a number between 1 and 100: 50
Too low! try again: 75
Too high! try again: 62
Congratulations!
The secret number was 62.
You guessed the number in 3 attempts.
```

## Future Improvements

- Difficulty levels (Easy, Medium, Hard)
- Replay option
- Input validation
- High score system
- Menu-based interface

## Author

Kalsoom

## License

This project is open-source and available for learning and practice.
