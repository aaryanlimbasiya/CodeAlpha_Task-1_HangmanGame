# CodeAlpha_Task-1_HangmanGame
Here is my FirstTask assigned from CODEALPHA.

# Overview

This project consists of two versions of the classic Hangman game implemented in Python. The first version is a basic text-based game, while the second version includes a visual representation of the hangman using ASCII art.

# Features

Basic Hangman Game:

*Randomly selects a word from a predefined list.

*Allows the player to guess letters to uncover the hidden word.

*Provides feedback on correct and incorrect guesses.

*Limits the number of incorrect guesses to 5.

*Displays the current state of the word after each guess.

*Ends the game with a win or loss message.

Hangman Game with Diagram:

*Includes a visual representation of the hangman using ASCII art.

*Randomly selects a word from a larger predefined list.

*Allows the player to guess letters to uncover the hidden word.

*Provides feedback on correct and incorrect guesses.

*Limits the number of incorrect guesses to 6.

*Displays the current state of the word and the hangman diagram after each guess.

*Ends the game with a win or loss message.


# Libraries Used:

random.choice(): Randomly selects a word from a predefined list.

# Variables:

HANGMAN: List of ASCII art representing hangman states.

words: List of possible words for the game.

chances: Number of incorrect guesses allowed.

# Game Loop:

Asks user to guess a letter.

Updates the displayed word if the guess is correct.

Displays the hangman diagram and reduces chances if the guess is incorrect.

Ends the game if all letters are guessed or chances run out.
