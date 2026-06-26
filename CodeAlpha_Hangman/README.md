# Hangman Game

A simple command-line implementation of the classic Hangman word-guessing game, written in Python.

## How to Play

1. Run the script using Python.
2. The game will select a random secret word.
3. You need to guess the word by suggesting letters one at a time.
4. You have **6 incorrect guesses** before you lose the game.
5. If you guess all the letters in the word correctly before running out of guesses, you win!

## How to Run

To start the game, run the following command in your terminal:

```bash
python GameCode
```

## Features

- **Random Word Selection**: Selects a word from a diverse predefined list of words.
- **Input Validation**: Ensures that only single alphabetic characters are accepted.
- **Duplicate Guess Prevention**: Prevents you from losing lives by guessing the same letter twice.
- **Real-time Status**: Displays the secret word with blank spots for unguessed letters, your remaining turns, and the list of letters you have already guessed.
