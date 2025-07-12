# Tenzies Game (React)

This is a simple dice game built using React. The goal of the game is to get all 10 dice to show the same number. You can click on any die to "hold" its value, and then keep rolling the rest until they all match.

## Features

- Dice roll and hold functionality
- Confetti animation when you win
- Timer that counts how long you take to win
- Dice face images instead of just numbers
- Roll button changes to "New Game" when game is won
- Keyboard accessibility and a screen reader message for win

## How to Play

1. Click "Roll" to start rolling the dice.
2. Click on a die to freeze its number.
3. Keep rolling the unfrozen dice.
4. Win when all dice show the same number.
5. Timer starts when the game begins and resets on new game.

## Tech Stack

- React (Functional components + Hooks)
- nanoid (for unique die IDs)
- react-confetti (for win animation)
- CSS Grid & Flexbox for layout

## Setup

1. Clone the repo
2. Run `npm install`
3. Run `npm start` to launch the game in the browser

