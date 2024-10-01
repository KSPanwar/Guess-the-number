# Number Guessing Game

## Overview
This is a simple number guessing game where a random number between 1 and 100 is selected, and the player must guess the number within 10 turns. The game provides feedback on whether the guess is too high or too low.

## Features
- Random number generation between 1 and 100.
- Allows up to 10 guesses.
- Visual feedback on guesses:
  - Correct guess: Highlights the success in green.
  - Incorrect guess: Indicates if the guess is too high or too low.
- Simple and intuitive UI with a design-friendly layout.

## Technologies Used
- **HTML** for structure.
- **CSS** for styling.
- **JavaScript** for game logic.

## How to Play
1. Enter a guess in the input field and click on the **Submit guess** button.
2. You will receive feedback on whether your guess was too high or too low.
3. Continue guessing until you find the correct number or run out of turns.
4. The game ends when you either guess the number or exhaust all 10 guesses.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/KSPanwar/Guess-the-number.git
2. Navigate to project directory
     cd number-guessing-game
3. Open the index.html file in any modern web browser
##  How It Works
A random number is generated when the game starts.
Players are allowed up to 10 guesses.
After each guess, the game will:
Keep track of all previous guesses.
Indicate whether the guess was too high or too low.
Display the result of the current guess (correct or incorrect).
When the game is over, the page will reset for a new round.
## Game Logic
The game uses JavaScript to:
Generate a random number.
Process user input.
Provide real-time feedback.
##License
This project is licensed under the MIT License.
