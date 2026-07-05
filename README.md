# Word Guessing Game

<img src="word%20guess.png" alt="Word Guessing Game" width="200" />

A simple, interactive terminal-based word guessing game developed in Python using fundamental programming structures. The game challenges players to deduce a randomly selected secret word letter by letter within a limited number of attempts.

## Features
* Random Word Selection: Leverages Python built-in random routines to select a unique target phrase each game iteration.
* Case Insensitive Input Tracking: Automatically handles player entry normalization to ensure smooth evaluation logic.
* Dynamic Game State Displays: Updates hidden letter markers in real time as correct characters are identified.
* Structural Turn Management: Tracks remaining incorrect attempts and dynamically provides a clear end-game summary for wins and losses.

## How to Run
1. Ensure Python 3.x is installed on your local environment.
2. Download or clone this repository.
3. Open a terminal or command prompt interface within the project directory.
4. Execute the application script using the command: python script_name.py

## Game Mechanics
* The software picks a hidden target phrase and represents it as an array of underscores.
* The user is granted exactly 10 incorrect guesses before facing elimination.
* Successfully guessing a character fills the respective blanks, while failing to match reduces your turn count.
* The game ends instantly upon revealing the complete word array or exhausting the available attempt counter.
