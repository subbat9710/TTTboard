# TTTboard
<<<<<<< HEAD
<<<<<<< HEAD

--- Project: Creating a Tic Tac Toe Game --- 

Setting up the Tic Tac Toe Game.
1 Setup the board
2 Set positons(also mark position)
3 Check for positons whether it is empty or full
4 Check whether the boad is full or not
5 If boad is full and check for winner, loser and tie

Basic strategy for Unbeatable Tic Tac Toe games
=======
Project: Creating a Tic Tac Toe Game.
=======
-- Project: Creating a Tic Tac Toe Game ---

->To run the app, try $ ruby app.rb in your terminal.

-> rackup required to load on port 4567
>>>>>>> 755e99c96d6b2b782bcdb669204b943fd2adbbe3

Setting up the Tic Tac Toe Game.

1 Setup the board

2 Set positons(also mark position)

3 Check for positons whether it is empty or full

4 Check whether the boad is full or not

5 If boad is full and check for winner, loser and tie

-- Basic strategy for Unbeatable Tic Tac Toe games --

>>>>>>> f7b62400a19489f16bbc3bcaffb07d93e00c783b
Win: If the player has two in a row, they can place a third to get three in a row.
Block: If the opponent has two in a row, the player must play the third themselves to block the opponent.
Fork: Create an opportunity where the player has two threats to win (two non-blocked lines of 2).
Blocking an opponent's fork:
Option 1: The player should create two in a row to force the opponent into defending, as long as it doesn't result in them creating a fork. For example, if "X" has a corner, "O" has the center, and "X" has the opposite corner as well, "O" must not play a corner in order to win. (Playing a corner in this scenario creates a fork for "X" to win.)
<<<<<<< HEAD
Option 2: If there is a configuration where the opponent can fork, the player should block that fork.
Center: A player marks the center. (If it is the first move of the game, playing on a corner gives "O" more opportunities to make a mistake and may therefore be the better choice; however, it makes no difference between perfect players.)
Opposite corner: If the opponent is in the corner, the player plays the opposite corner.
Empty corner: The player plays in a corner square.
Empty side: The player plays in a middle square on any of the 4 sides.

->  Here is my link for the TTTboard https://teelatictactoe.herokuapp.com/
=======
    Option 2: If there is a configuration where the opponent can fork, the player should block that fork.
    Center: A player marks the center. (If it is the first move of the game, playing on a corner gives "O" more opportunities to make a mistake and may therefore be the better choice; however, it makes no difference between perfect players.)
    Opposite corner: If the opponent is in the corner, the player plays the opposite corner.
    Empty corner: The player plays in a corner square.
    Empty side: The player plays in a middle square on any of the 4 sides.
   
For more references: https://en.wikipedia.org/wiki/Tic-tac-toe

  ->  Here is my link for the TTTboard https://teelatictactoe.herokuapp.com/
>>>>>>> f7b62400a19489f16bbc3bcaffb07d93e00c783b
