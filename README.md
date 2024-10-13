# Number Guessing Game from 100 Days of Code

This is a beginner-friendly Number Guessing Game implemented in Python. The game randomly selects a number between 1 and 100, and the player must guess the correct number within a limited number of attempts. Players can choose between two difficulty levels: easy, which provides 10 attempts, and hard, which offers 5 attempts.

## How to Play

1. Run the game script.
2. Choose a difficulty level: type `easy` for 10 attempts or `hard` for 5 attempts.
3. Enter a number between 1 and 100 as your guess.
4. The game will give feedback on whether your guess is too high, too low, or correct.
5. Continue guessing until you either find the correct number or run out of attempts.

## Skills Demonstrated

- **Basic Input/Output Handling**: Using `print()` to interact with the player and `input()` to capture user input.
- **Conditional Statements**: Utilizing `if`, `elif`, and `else` to manage game logic based on user choices and feedback.
- **Loops**: Implementing `while` loops to allow for repeated guesses and to prompt the user until a valid difficulty is selected.
- **Error Handling**: Basic input validation to ensure correct difficulty selection.
- **Logical Operators**: Using `or` to handle multiple conditions within the main loop.
- **Increment/Decrement Operations**: Tracking remaining attempts by decrementing counters (`hard_count` and `easy_count`).
- **Variable Management**: Defining and updating variables to maintain game state.
- **Random Number Generation**: Using Python's `random` module to generate a random number.

