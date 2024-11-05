# Hangman Game

This is a simple, text-based Hangman game implemented in Python. The player must guess the hidden word letter by letter, before exceeding 6 guesses of incorrect guesses. 

## Features
- ASCII art visuals for each stage of the game to represent the hangman's progress.
- Random word selection from a `words.txt` file.
- Input validation to ensure guesses are single letters and prevent repeated guesses.
- Game feedback after each guess, indicating correct and incorrect guesses.
- Option to play again after each game.

## Getting Started

### Prerequisites
- Python 3.x
- A text file named `words.txt` in the same directory as the script, containing a list of words (one word per line).

### How to Run the Game
1. Clone or download this repository.
2. Ensure that `words.txt` is present in the same directory as the `hangman.py` file.
3. Run the game in console.
   
# Game Rules:
- The game will display blanks for each letter of the randomly selected word.
- Guess one letter at a time.
- Each incorrect guess brings the player one step closer to "hanging" the stick figure.
- If the word is guessed correctly within the allowed attempts, the player wins.
- If the player reaches the maximum number of incorrect guesses, they lose, and the word is revealed.
