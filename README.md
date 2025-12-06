# 2048-games

Overview
This project implements the classic 2048 puzzle game using Pygame in Python. Players slide numbered tiles on a 4x4 grid to combine matching numbers and achieve the 2048 tile. The game features smooth animations, colorful tile designs, and standard win/lose conditions.​

Features
4x4 grid with animated tile movements for left, right, up, and down directions.
Tiles merge when matching values collide, doubling the number and changing colors based on value.
Random generation of 2s or 4s in empty cells after valid moves.
Game over detection when grid fills without possible moves.
Visual grid outlines, background, and centered tile numbers with Comic Sans font.​

Requirements
Python 3.x
Pygame library (pip install pygame)
No additional dependencies required beyond Pygame for graphics and input handling.​

Installation
Clone or download the repository containing main.py.
Install Pygame: pip install pygame.
Run the game: python main.py.

The game window opens at 650x650 pixels with the title "2048 KALNA H TO KHELO". Use arrow keys to play.​

Controls
Arrow keys: Left, Right, Up, Down to move tiles.
Close window or press key after game over to exit.

Game Rules
Combine tiles to reach 2048. Game ends on full grid with no merges possible. Highest score tracked implicitly through largest tile.​

Project Structure
main.py: Complete game implementation including Tile class, movement logic, drawing functions, and main loop.
