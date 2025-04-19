# Custom Tic Tac Toe with Drag and Drop

This is a custom version of the classic Tic Tac Toe game with added features like drag-and-drop piece movement, restricted "L-moves", and win condition highlighting. It allows players to place and move their pawns one step at a time while adhering to specific movement rules.

## Features
- **Drag-and-Drop Mechanics**: Players can drag and drop their pieces on the board.
- **Restricted L-Moves**: Certain "L-shaped" moves are blocked if the game starts from the top-left corner.
- **Winning Combos Highlighted**: The winning combination is visually highlighted with a strikethrough.
- **Real-time Gameplay**: The game alternates turns between two players, and the status is updated after each move.
- **Game Reset**: Easily restart the game with a button click.

## Game Rules
- Each player can place up to 3 pawns on the board.
- After placing a pawn, players can move their existing pawns one step at a time.
- Players cannot jump over their opponent's pawns.
- The game is won when a player aligns 3 pawns horizontally, vertically, or diagonally.
- If the game starts from the top-left corner (index 0), "L-shaped" moves are restricted.

## Setup

### Prerequisites
- Web browser (for playing the game)

### Running the Game Locally
1. Clone the repository:
   ```bash
   https://github.com/astaputhra/TictacToe.git
