# TTTboard
--- Project: Creating a Tic Tac Toe Game --- 

Descriptions: This project is totally about the Tic Tac Toe game. There are four main features of the game. First about the human. Human plays against Human. Second about Human plays against sequential(computer playes sequently). It also called easy game in this project. Third about human plays against Random player(computer plays randomly). It also called medium game in this project. Last or fourth is about the Human plays against Unbeatable(Computer plays unbeatable. It means impossible to win the computer). This section also called Hard game in this project.

Setting up Tic Tac Toe Game.
=======
1 Setup the board

2 Set positons(also mark position)

3 Check for positons whether it is empty or full

4 Check whether the boad is full or not

5 If boad is full and check for winner, loser and tie

->To run the app, try $ ruby app.rb in your terminal.

-> rackup required to load on port 4567(mac)

Basic strategy for Unbeatable Tic Tac Toe games
=======
Win: If the player has two in a row, they can place a third to get three in a row.
Block: If the opponent has two in a row, the player must play the third themselves to block the opponent.
Fork: Create an opportunity where the player has two threats to win (two non-blocked lines of 2).
Blocking an opponent's fork:
Option 1: The player should create two in a row to force the opponent into defending, as long as it doesn't result in them creating a fork. For example, if "X" has a corner, "O" has the center, and "X" has the opposite corner as well, "O" must not play a corner in order to win. (Playing a corner in this scenario creates a fork for "X" to win.)

Option 2: If there is a configuration where the opponent can fork, the player should block that fork.
Center: A player marks the center. (If it is the first move of the game, playing on a corner gives "O" more opportunities to make a mistake and may therefore be the better choice; however, it makes no difference between perfect players.)
Opposite corner: If the opponent is in the corner, the player plays the opposite corner.
Empty corner: The player plays in a corner square.
Empty side: The player plays in a middle square on any of the 4 sides.
   
For more references: https://en.wikipedia.org/wiki/Tic-tac-toe

  ->  Here is my link for the TTTboard https://teelatictactoe.herokuapp.com/