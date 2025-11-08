# Catch Game
A simple browser-based catch game built with **Phaser 3**, where players move a basket to catch falling apples and earn points. Reach the target score within the time limit to win.

## Table of Contents
- Project Overview
- Gameplay
- Technologies Used
- Installation
- Usage
- Features
- Project Structure
- Future Improvements
- Git Push

## Project Overview
This project is a simple arcade game designed for learning and practicing game development using Phaser 3. The main goal is to move a basket horizontally to catch falling apples and earn points. The game features a timer, scoring system, and end screens for success or failure.

## Gameplay
- Players control a basket using the arrow keys (left and right)
- Apples fall from the top of the screen at a constant speed
- Catching an apple earns 1 point
- The game runs for 15 seconds
- If the player scores 10 points or more, a success screen is shown; otherwise, a try-again screen is displayed

## Technologies Used
- Phaser 3 – Game framework
- JavaScript (ES6) – Game logic
- HTML & CSS – UI and styling
- Webpack / Vite – For bundling (if applicable)

## Installation
1. Clone the repository:
git clone https://github.com/Oyewolesyl/Dev-5-FrontEnd-Assignment-Phaser.git
2. Navigate into the project folder:
cd Dev-5-FrontEnd-Assignment-Phaser
3. Install dependencies:
npm install
4. Start the development server:
npm run dev
5. Open `index.html` in your browser (or use the dev server URL)

## Usage
- Click Start to begin the game
- Move the basket using Left / Right arrow keys
- Catch apples to earn points
- Watch the timer and aim to score 10 or more points to win
- At the end of the game, view your score and win/lose status

## Features
- Responsive canvas that scales to screen size
- Physics-based falling objects using Phaser Arcade Physics
- Live score updates
- Timer-based game loop
- Win/lose end screen with dynamic messages
- Sound effects for catching items and background music
- Particle effects when catching apples

## Project Structure
project-root/
├── assets/          # Images and audio files
├── src/             # Source JavaScript code
│   ├── main.js
│   └── style.css
├── index.html
├── package.json
└── README.md


