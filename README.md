# ce-ris specifications
The game randomly generates tetriminos (4-piece block shapes) to fall from the top of the screen.
The tetriminos fall at increasing speeds incremented at every one minute of game play.
The tetriminos fall and stack directly upon whatever is below them, whether it be the bottom of the scream or another tetrimino piece. 
A ghost piece is displayed at the bottom of the screen to determine where the tetriminos will land if it was dropped from its current position. The ghost piece’s x-position changes based on the tetrimino’s x-position, and the y-position changes based on what other tetriminos are beneath it. Additionally, the ghost piece rotates in the same direction when the player rotates the tetrimino.  
The game clears a horizontal line of blocks once it is filled with tetriminos pieces. All the blocks above that row move one row down so that there is no empty space at the bottom of the screen.
If a brick can not fit onto the screen, the game is over. 
Score is calculated based on how many rows are cleared overall and how many rows are cleared at one time. 
The player is able to move the tetrimino left and right using the left and right arrow keys. 
The player can either drop the tetrimino incrementally using the down arrow key or “hard drop” the piece at once using the spacebar. 
The player can rotate the piece right using the up arrow key or rotate left using the Z arrow key. 
The Escape key pauses the game.
