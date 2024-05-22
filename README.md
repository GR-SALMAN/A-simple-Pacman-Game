# SPAC-MAN Game

Welcome to SPAC-MAN, a simple yet exciting game built using C++. Navigate the maze, collect points, and avoid the ghost. Can you beat the high score?

## Features

- **Different Difficulty Levels**: Choose between Easy, Normal, and Hard modes.
- **Classic Gameplay**: Move your character using arrow keys to collect points.
- **Challenging AI**: Avoid the ghost that chases you through the maze.
- **Score Display**: Keep track of your score in real-time.

## Getting Started

### Prerequisites

- Windows OS
- C++ Compiler (e.g., GCC)
- Command Line or Terminal

### Installation

1. **Clone the Repository**:

   ```bash
      git clone https://github.com/yourusername/spac-man.git
      cd spac-man
2. **Compile the Game**:

Open your command line or terminal in the project directory and run the following command:

   ```bash
      g++ -o spacman main.cpp
   ```
3. Run the Game:
   ```bash
      ./spacman
   ```
## How to Play

### Start the Game:

- After running the game, you'll see a welcome screen with instructions and difficulty options.

#### Choose Difficulty:

### Select your preferred difficulty level by entering:

- H for Hard
- N for Normal
- E for Easy
### Control Your Character:

#### Use the arrow keys to move your character (H) around the maze:

- ↑ to move up
- ↓ to move down
- ← to move left
- → to move right
- Collect Points:

Move over dots (.) to collect points. Your current score is displayed in the top right corner.

### Avoid the Ghost:

Avoid the ghost (Q) that chases you. If the ghost catches you, the game ends.

### Game Over:

When caught by the ghost, the game will display your score and end.

#### Code Overview
main.cpp: Contains the game logic and main loop.
Map Rendering: Uses printf to display the game map and gotoxy to control cursor position for dynamic updates.
Entity Movement: Defines an entity class for player movement and a simple AI for ghost movement using BFS (Breadth-First Search) for pathfinding.
### Contributing
Feel free to fork this project, submit issues, and create pull requests. Contributions are always welcome! 

>Suggested to use CodeBlocks in order to buid & run
