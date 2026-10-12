# 2048 Game

A fully functional, interactive implementation of the classic 2048 puzzle game built with vanilla JavaScript (ES6+ classes), HTML5, and CSS/SCSS. Slide tiles, merge numbers, keep track of your score, and try to reach the 2048 tile!

[Visit the Website](https://<your_account>.github.io/2048_game/)

## Technologies Used
- HTML5
- CSS3 / SCSS
- Vanilla JavaScript (ES6+ Classes, OOP architecture)
- Git & GitHub Pages

##Features & Game Mechanics

**4x4 Game Grid:** Classic board structure supporting standard grid movements.

**Keyboard Controls:** Use arrow keys (ArrowUp, ArrowDown, ArrowLeft, ArrowRight) to slide and merge tiles across the board.

**Smart Merging Logic:**

Adjacent equal cells combine into a doubled value.
Multi-merging prevention rules applied per single move.

**Random Tile Generation:** After each valid move, a new tile (2 or 4) appears in a random empty cell (with a 10% probability for 4).

**Score Tracking:** Real-time score updates calculated dynamically based on the sum of all merged cells.

**Game States:**

Dynamic UI transitions for Start and Restart buttons.

Built-in win notification when reaching the 2048 tile.

Game Over detection when no legal moves remain.

Modular Architecture: Core game logic isolated within a dedicated Game class module (src/modules/Game.class.js) separate from UI event handling.

## Getting Started

To get a local copy up and running, follow these simple steps:

1. **Clone the repository:**
git clone

2. **Install dependencies:**
npm install

3. **Run the project locally:**
npm start
