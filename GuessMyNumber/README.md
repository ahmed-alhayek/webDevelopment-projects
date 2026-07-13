# Guess My Number!

## Overview
"Guess My Number!" is a simple, interactive web game where the player must guess a randomly generated secret number between 1 and 20. It features a clean retro-style interface and provides instant feedback on your guesses.

## How It Works & Features
* **Score Tracking:** The player begins with a score of 20. Every time an incorrect guess is made, the score drops down by 1 
* **Dynamic Messages:** The game guides the player by displaying messages like "📈 Too high!" or "📉 Too low!" based on their input
* **Highscore System:** The program keeps track of your best performance. If a player guesses correctly and their current score is higher than the existing high score, the high score is updated.
* **Reset Functionality:** Clicking the "Again!" button resets the game completely—generating a new secret number, restoring the score to 20, and resetting the interface colors—but it preserves your highest score so you can keep trying to beat it.
* **Visual Feedback:** When the correct number is guessed, the screen background turns green and the number box expands to celebrate the win

## Development Notes & The DRY Principle
As part of my continuous journey learning web development, a major focus of this project was writing clean, optimized JavaScript by strictly following the **DRY (Don't Repeat Yourself)** principle.

If you look at the `script.js` file, you will notice commented-out lines of code at the bottom. These represent the initial, repetitive logic used to check if a guess was too high or too low To improve the codebase, I refactored this by:
1. **Consolidating conditionals:** Replacing the separate `guess > secretNumber` and `guess < secretNumber` blocks with a single `guess !== secretNumber` block, using a ternary operator to handle the specific message 
2. **Creating helper functions:** Implementing a `displayMessage` function to update the text content, which eliminated the need to repeatedly write `document.querySelector('.message').textContent` throughout the program
