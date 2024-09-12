# Tic-Tac-Toe Game
![](https://img.freepik.com/premium-vector/tic-tac-toe_854558-122.jpg)

This is a C implementation of the classic Tic-Tac-Toe game, where the player can compete against the computer. The computer uses the Minimax algorithm to make intelligent moves.

## How to Play

### Rules
- The game is played on a 3x3 grid.
- The player uses 'X', and the computer uses 'O'.
- Players take turns placing their symbol (X or O) in one of the 9 cells.
- The goal is to get three of your marks in a row, column, or diagonal.
- The first player to get three in a row wins.
- If all 9 cells are filled without any player achieving a win, the game ends in a draw.

### How to Run
1. **Compile the Program**: Use a C compiler to compile the code.
   ```bash
   gcc tic_tac_toe.c -o tic_tac_toe
   ```
2. **Run the Program**: Execute the compiled program.
   ```bash
   ./tic_tac_toe
   ```
3. **Gameplay**:
   - The game will display a numbered board.
   - When it's your turn, enter a number (1-9) corresponding to the cell where you want to place your 'X'.
   - The computer will then make its move.
   - The game continues until there's a winner or a draw.

### Example
```
Tic-Tac-Toe

Choose a cell numbered from 1 to 9 as below and play

         1 | 2 | 3 
        --------------
         4 | 5 | 6 
        --------------
         7 | 8 | 9 

Enter your move (1-9): 1

COMPUTER has put a O in cell 1 1
         O |   |   
        --------------
           |   |   
        --------------
           |   |   

```

## Files
- `tic_tac_toe.c`: The source code for the game.
- `README.md`: This file, containing instructions on how to compile, run, and play the game.

## Dependencies
- Standard C library headers: `stdbool.h`, `stdio.h`, `stdlib.h`, `time.h`.

## Algorithm
The computer's moves are determined using the Minimax algorithm, which evaluates all possible moves and chooses the one that maximizes the computer's chance of winning or minimizes the player's chance of winning.

## Contact
- [LinkedIn](https://www.linkedin.com/in/urvashi-kashyap-38117522a/)
- [GitHub](https://github.com/urvashikashyap16)
