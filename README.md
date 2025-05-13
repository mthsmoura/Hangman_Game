# Hangman Game

## Summary
Hangman is a classic word-guessing game implemented in Python. The player must guess a hidden word one letter at a time. Each incorrect guess brings the player closer to "hanging" — visually represented by drawing parts of a stick figure. The game ends in victory when the player correctly guesses the word, or defeat when the figure is fully drawn.

## Overview
At the beginning of each game, a random word is selected and displayed as a series of underscores (_), with each underscore representing a hidden letter. The player then attempts to guess the word by entering one letter per round:

- Correct guesses reveal all occurrences of the letter in the word.
- Incorrect guesses increase the mistake count and draw part of the hangman.

The game ends when either:
- The player successfully reveals the full word (win), or
- The player makes six incorrect guesses (loss).

The name *Hangman* refers to the visual metaphor of drawing a stick figure being hanged after each mistake.

## Languages and Libraries Used
- **Python**
- No external libraries were required – the game uses only built-in Python functionality.

## Key Learning
- Reinforced understanding of Python basics such as:
  - Strings and lists manipulation
  - Loops and conditionals
  - Functions and control flow
  - User input handling
- Practiced clean code structure and basic game logic
- Improved ability to implement text-based interactive programs

---

Feel free to clone this repository and try the game yourself!
