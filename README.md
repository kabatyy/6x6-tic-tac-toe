# 6-6-Tic-Tac-Toe
The game is based on the common 3x3 tic-tac-toe game, but expanded to a 6x6 area. In basic tic-tac-toe, a player wins the game by achieving 3 symbols in a row, and to expand on this concept, the winner of this configuration will need to achieve 4 in a row. The foundational execution of the game will be based on comparing two player strategies. One player will be an alpha-beta search with heuristic cutoff, and another will be a query (human) player. Each player will be evaluated based on the win rate, number of moves, and execution time.

# Running the Code
There are two modes available: 
- Interactive: Run this block to play against the alpha-beta algorithm. Once prompted enter a value from 0-5 to indicate the column number and then the row number. 
- Automated Evaluation: Run this block to evaluate the alpha-beta algorithm against a random player. This will then provide the win rate, average moves, and execution time across 10 games. 
