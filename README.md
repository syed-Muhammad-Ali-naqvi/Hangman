Hangman Game

Introduction

This is a simple Hangman game written in Python. The game challenges players to guess a hidden word, one letter at a time, within a limited number of attempts.

Features

Random word selection from a predefined list.

Interactive gameplay with real-time feedback.

Tracks remaining lives and notifies when the game is won or lost.

How to Play

When you start the game, you will be greeted with a prompt asking for your name and whether you have played a similar game before.

A hidden word will be selected randomly from the predefined word list.

The hidden word will be represented by underscores (_), showing the number of letters in the word.

You will have 6 lives to guess the correct letters of the hidden word.

For each incorrect guess, you lose a life.

For each correct guess, the corresponding underscores are replaced by the guessed letter.

The game ends when:

You correctly guess all the letters in the hidden word.

You run out of lives.

Word List

The hidden words are chosen randomly from the following list:

"python", "developer", "analyst", "scientist", "programming", "pakistan", "mathematics", "karachi", "comedy", "debug", "dictionary", "poetry", "spreadsheet", "hangman", "landcruiser", "algorithm"

How to Run the Game

Make sure you have Python installed on your system.

Copy the script into a .py file, for example, hangman.py.

Run the script in your terminal or IDE using the command:

python hangman.py

Follow the prompts to play the game.

Example Gameplay

Start:

Game: HANGMAN.

What is your name? John
Have you ever played a game like this one? Yes or No: Yes
Here is the hidden word:
['_', '_', '_', '_', '_', '_']

During Gameplay:

Guess a letter: p
['p', '_', '_', '_', '_', '_']

Guess a letter: x
Unmatch: Attempts remaining: 5

Guess a letter: y
['p', 'y', '_', '_', '_', '_']

Winning:

You won!
The hidden word was python

Losing:

Unmatch: Attempts remaining: 0
You have come out of the limitation of attempts!!
The hidden word was: python

Notes

This version of the game is a basic implementation and can be further enhanced by:

Adding graphics or animations.

Importing external modules for better aesthetics (e.g., hangman_art).

Improving error handling for invalid inputs.

License

This project is open-source and can be modified or shared freely.

