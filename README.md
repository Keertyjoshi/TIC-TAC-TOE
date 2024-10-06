# TIC-TAC-TOE
Here's a simple and effective `README.md` for your Tic-Tac-Toe game project using Python and Tkinter:

---

# Tic-Tac-Toe with AI (Minimax Algorithm)

This is a Python-based Tic-Tac-Toe game where the player competes against an AI opponent. The AI uses the Minimax algorithm to make optimal decisions, ensuring that it always plays its best possible move. The game is built with the Tkinter library for the graphical user interface (GUI).

## Features

- **Player vs AI**: The player uses "X", while the AI uses "O". After every player move, the AI calculates its best move using the Minimax algorithm.
- **AI with Minimax**: The AI guarantees the best possible outcome by using the Minimax algorithm, ensuring it either wins or forces a draw if played optimally.
- **Simple GUI**: The game uses Tkinter for the graphical interface, with buttons representing the game board.

## Game Rules

- The game is played on a 3x3 grid.
- The player goes first, playing with "X".
- The objective is to get three of your marks in a row (horizontally, vertically, or diagonally) before the AI does.
- The game will end in a win, draw, or when no moves are left.

## Installation and Setup

1. **Prerequisites**: Make sure Python 3 is installed on your system.
   
   - Install the required Tkinter module if not already installed:
     ```bash
     sudo apt-get install python3-tk  # For Linux/Ubuntu
     ```
     Tkinter usually comes pre-installed with Python on Windows and macOS.

2. **Download/Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/tic-tac-toe-ai.git
   cd tic-tac-toe-ai
   ```

3. **Run the Game**:
   Run the following command to start the game:
   ```bash
   python tic_tac_toe.py
   ```

## How the Game Works

- The player clicks on one of the buttons in the 3x3 grid to place their "X".
- The AI then calculates its best move and places an "O".
- The game checks for a win after every move. If there's a winner, the game will display a message box declaring the winner and close the window.
- If all cells are filled and no one has won, the game declares a draw.

## Code Explanation

- **Main GUI**: Tkinter is used to create the 3x3 button grid where players make moves.
- **Minimax Algorithm**: The AI uses the Minimax algorithm to evaluate all possible moves and picks the one that maximizes its chance of winning (or minimizes the player's chance of winning).
- **Game Logic**: The game continuously checks for winning conditions after each move, for both the player and the AI. If no spaces remain and no winner is declared, the game is a draw.

## Future Enhancements

- Add an option to restart the game after it ends, without closing the window.
- Implement a scoreboard to track wins, losses, and draws.
- Option to play against another player (Player vs Player mode).
- Difficulty levels for AI (e.g., random moves, easy AI, hard AI).

## Contributing

Feel free to contribute to this project by submitting pull requests or opening issues.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

