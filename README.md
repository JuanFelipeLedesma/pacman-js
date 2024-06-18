Pac-Man Game
This project is a classic Pac-Man game developed in JavaScript, HTML, and CSS. The game was initially created by another developer, and we have taken it upon ourselves to fix several bugs and malfunctions to improve the gameplay experience. This project demonstrates our skills in these programming languages and our ability to debug and enhance existing code.

Original Game Source
The original game was developed by [Original Developer's Name] and had several functionalities in place. However, there were a few bugs and issues that needed to be addressed to ensure smooth gameplay.

Bug Fixes and Enhancements
1. Ghosts Movement Bug
Issue: Ghosts would occasionally stop moving and remain stationary.
Fix: We revised the logic in ghost.js to ensure that ghosts continuously move and do not get stuck. The movement process and collision detection were improved to prevent ghosts from becoming stationary.
2. Map Alignment Issue
Issue: The map had an unwanted space of approximately 1 cm on the right side.
Fix: We dynamically set the canvas size based on the map dimensions to ensure there is no extra space on the right side. This ensures that the map aligns perfectly with the last block on the right, just like it does on the left.
3. Pac-Man Tunneling Implementation
Feature: Implemented the tunneling feature for Pac-Man. When Pac-Man exits the map on the right, he re-enters from the left, and vice versa. This improves the gameplay experience by allowing seamless movement across the edges of the map.
4. Game Reset on Zero Lives
Feature: Implemented an automatic game reset when Pac-Man's lives reach 0. This ensures that the game restarts from the beginning, allowing continuous gameplay without manual intervention.
5. Display Score and Lives
Issue: The score and lives display menu was missing or misaligned.
Fix: Adjusted the canvas height to include an area for displaying the score and lives. Ensured that the menu displays correctly at the bottom of the canvas.
6. Number of Ghosts
Enhancement: Ensured that only 4 ghosts are displayed, one of each color, to match the classic Pac-Man experience.
How to Play
Movement:

Use the arrow keys or WASD keys to move Pac-Man.
Pac-Man can move up, down, left, or right to navigate the maze and eat all the food pellets.
Tunneling:

Pac-Man can exit the map from the right and re-enter from the left, and vice versa.
Ghosts:

Avoid the ghosts that roam the maze. If Pac-Man collides with a ghost, he loses a life.
The game resets when Pac-Man's lives reach 0.
Installation
Clone this repository to your local machine.
bash
Copiar código
git clone https://github.com/your-repo/pacman-game.git
Open the pacman.html file in your web browser to start playing the game.
Technologies Used
JavaScript: Game logic and functionality.
HTML: Game structure and canvas element.
CSS: Basic styling for the game.
Contributions
We have made significant improvements to the original code, fixing bugs and adding new features. This project demonstrates our ability to:

Debug and enhance existing JavaScript code.
Work with HTML and CSS to create a seamless user experience.
Implement classic game features such as tunneling and automated resets.
Credits
Original game developed by [Original Developer's Name].
Improvements and bug fixes by Juan Felipe Ledesma.
License
This project is licensed under the MIT License - see the LICENSE file for details.

We hope you enjoy playing this improved version of the Pac-Man game! If you have any suggestions or find any issues, please feel free to contribute or open an issue in the repository.
