# Python Blackjack Game

This Python script is a simple implementation of the Blackjack card game. It features basic game logic where you can play against the computer in the console.

## Features

- **Random card dealing**: Each card drawn in the game is randomly selected.
- **Automatic score calculation**: The game calculates scores automatically, taking into account the rules of Blackjack.
- **Game decisions**: Players can choose to draw more cards or stop based on their current score.

## How to Play

1. Run the script.
2. The game will ask if you want to play a round of Blackjack. Type `y` to start or `n` to exit.
3. You will see your cards and one of the computer's cards.
4. Choose whether to draw another card or pass by typing `y` or `n`.
5. The game will continue until you pass or go over a score of 21.
6. The computer plays its hand according to the rules, drawing cards until it reaches a minimum score of 17.
7. The scores are compared and the result is announced.

## Rules

- The goal is to have a score closer to 21 than the computer without exceeding 21.
- Number cards count as their face value, face cards (Jack, Queen, King) count as 10, and Ace can count as 1 or 11.
- A score of 21 on the initial deal is called a "Blackjack" and is an automatic win unless the computer also has a Blackjack, resulting in a draw.

## Modules Used

- `random` for card dealing.
- `replit` to clear the screen after each round (specific to Repl.it platform).
- `art` for ASCII art, specifically the `logo` used in the game interface (if available).

## Gameplay Example

```plaintext
Do you want to play a game of Blackjack? Type 'y' or 'n': y
   Your cards: [10, 5], current score: 15
   Computer's first you: [10]
Type 'y' to get another card, type 'n' to pass: y
   Your final hand: [10, 5, 6], final score: 21
   Computer's final hand: [10, 7], final score: 17
You win 😃
