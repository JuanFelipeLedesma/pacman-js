# Pac-Man Game

This project is a classic Pac-Man game developed in JavaScript, HTML, and CSS. The game was initially created by another developer, and we have taken it upon ourselves to fix several bugs and malfunctions to improve the gameplay experience. This project demonstrates our skills in these programming languages and our ability to debug and enhance existing code.

## Original Game Source

The original game was developed by [Original Developer's Name] and had several functionalities in place. However, there were a few bugs and issues that needed to be addressed to ensure smooth gameplay.

## Bug Fixes and Enhancements

### Ghosts Movement Bug
- **Issue**: Ghosts would occasionally stop moving and remain stationary.
- **Fix**: We revised the logic in `ghost.js` to ensure that ghosts continuously move and do not get stuck. The movement process and collision detection were improved to prevent ghosts from becoming stationary.

### Map Alignment Issue
- **Issue**: The map had an unwanted space of approximately 1 cm on the right side.
- **Fix**: We dynamically set the canvas size based on the map dimensions to ensure there is no extra space on the right side. This ensures that the map aligns perfectly with the last block on the right, just like it does on the left.

### Pac-Man Tunneling Implementation
- **Feature**: Implemented the tunneling feature for Pac-Man. When Pac-Man exits the map on the right, he re-enters from the left, and vice versa. This improves the gameplay experience by allowing seamless movement across the edges of the map.

### Game Reset on Zero Lives
- **Feature**: Implemented an automatic game reset when Pac-Man's lives reach 0. This ensures that the game restarts from the beginning, allowing continuous gameplay without manual intervention.

### Display Score and Lives
- **Issue**: The score and lives display menu was missing or misaligned.
- **Fix**: Adjusted the canvas height to include an area for displaying the score and lives. Ensured that the menu displays correctly at the bottom of the canvas.

### Number of Ghosts
- **Enhancement**: Ensured that only 4 ghosts are displayed, one of each color, to match the classic Pac-Man experience.

## How to Play

1. **Movement**:
   - Use the arrow keys or `WASD` keys to move Pac-Man.
   - Pac-Man can move up, down, left, or right to navigate the maze and eat all the food pellets.

2. **Tunneling**:
   - Pac-Man can exit the map from the right and re-enter from the left, and vice versa.

3. **Ghosts**:
   - Avoid the ghosts that roam the maze. If Pac-Man collides with a ghost, he loses a life.
   - The game resets when Pac-Man's lives reach 0.

## Installation

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-repo/pacman-game.git
