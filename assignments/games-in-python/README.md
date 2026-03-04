# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python using strings, loops, and conditionals. By completing this assignment, you will practice handling user input, tracking game state, and writing clear game logic.

## 📝 Tasks

### 🛠️	Set Up the Game Word and State

#### Description
Create the initial setup for the Hangman game. Start with a predefined list of words, randomly choose one word for the current game, and initialize the variables needed to track guessed letters and remaining attempts.

#### Requirements
Completed program should:

- Include a predefined list of possible words.
- Randomly select one word at the beginning of the game.
- Initialize a collection to store guessed letters.
- Initialize a counter for incorrect guesses remaining.


### 🛠️	Implement the Game Loop

#### Description
Build the main game loop where the player guesses one letter at a time. After each guess, update and display the current word progress, reduce attempts for incorrect guesses, and end the game with a clear win or lose message.

#### Requirements
Completed program should:

- Prompt the player to enter a letter guess.
- Display the word progress using underscores for unguessed letters (for example: `_ _ n g m a n`).
- Decrease remaining attempts only when the guess is incorrect.
- End with a win message when all letters are guessed.
- End with a lose message when attempts run out and reveal the word.
