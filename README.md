# Pass the Pig Game

Welcome to my **Pass the Pig** game repository! This is a fun, two-player dice game I created as part of my learning journey through the **Udemy course: "The Complete JavaScript Course"** by Jonas Schmedtmann. You can find the course here: [The Complete JavaScript Course](https://www.udemy.com/course/the-complete-javascript-course/). This project applies the JavaScript skills I’ve learned, including DOM manipulation, event handling, and game logic.

## About This Project

"Pass the Pig" is a simplified version of the classic Pig Game, where two players take turns rolling a die to accumulate points. The catch? Rolling a 1 resets your turn’s score, and you must decide when to "hold" your points to avoid losing them. The first player to reach 100 points wins!

### Skills Applied
This project showcases the following JavaScript concepts from the Udemy course:
- **DOM Manipulation**: Updating scores, showing/hiding the dice, and toggling player states.
- **Event Listeners**: Handling clicks for rolling, holding, resetting, and showing instructions.
- **Functions**: Modular code for rolling dice, switching players, and managing game state.
- **Conditionals**: Logic for winning conditions and turn resets.
- **Variables & Scope**: Tracking scores, current player, and game status.

## Features
- **Two-Player Gameplay**: Players alternate turns rolling a die.
- **Roll Dice**: Adds the roll value to the current score unless a 1 is rolled, which resets the turn.
- **Hold Score**: Bank your current score and pass the turn to the other player.
- **Win Condition**: First player to reach 100 points wins, with a visual victory state.
- **New Game**: Reset the game to start over.
- **How to Play Modal**: Displays instructions, closable via button, overlay click, or Escape key.
- **Visual Feedback**: Active player highlighting, dice display, and winner styling.

## Files Included
- `script.js`: The core JavaScript logic for the game (provided above).
- `index.html`: HTML structure with player sections, buttons, and a modal.
- `style.css`: Styling for the game layout, dice, and modal.
- `dice-1.png` to `dice-6.png`: Images for the dice faces.

## How to Play
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/charlierobertsuk/pass-the-pig.git
   ```
2. **Open the Game**:
   - Navigate to the project folder.
   - Open `index.html` in a web browser (e.g., Chrome, Firefox).
3. **Game Rules**:
   - Players take turns rolling the die by clicking "Roll Dice".
   - Each roll adds to your "Current" score unless you roll a 1, which resets your turn’s score to 0 and switches players.
   - Click "Hold" to add your current score to your total and pass the turn.
   - First to 100 points wins!
   - Click "New Game" to reset, or "How to Play" for instructions.

## Setup
- No additional dependencies are required—just a modern web browser.
- Ensure the dice images (`dice-1.png` to `dice-6.png`) are in the same directory as `index.html`.

## Acknowledgments
- Huge thanks to **Jonas Schmedtmann** for his excellent course, which provided the foundation for this project.
- This game is an adaptation of the "Pig Game" project from [The Complete JavaScript Course](https://www.udemy.com/course/the-complete-javascript-course/), personalized with my own naming and tweaks.
