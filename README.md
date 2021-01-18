# <u>Assignment Sankes & Ladders</u>

**Designing and implementing a Snakes and Ladders game in Python.**

- The game consists of 2 modes: Auto mode and Cheat/Manual mode.

- For auto mode, a player will type `roll` and a random number will be generated
  imitating the roll of dice. 
 
- There are 6 face dice which are being rolled by the player to their
  chance.
  
- For a manual mode, instead of entering roll, players can enter any number between `1 and 20`.
  
- The player starts from 0 and has to reach the final position (in our case,
  it's 100).
  
- There are some ladders which turn out to be lucky for the player as
  they shorten the way.
  
- There are some snakes present in between the game which turns out
  to be the enemy of the player as they just lengthen their way to 100.
  
- The position of snakes and ladders are stored in start:end format
  where start denotes the position of ladder/snake and end denotes the
  value that it reaches.
  
- There are only 2 players in the game and no spectators 

- During any player’s chance, if he/she enters `quit`, then
  the game will instantaneously end for that particular player and the other
  player will win the game.
  
`Position of snakes: {17 : 7, 54 : 34, 62 : 19, 98 : 79}`
`Position of ladders: {3 : 38, 24 : 33, 42 : 93, 72 : 84}`
<hr></hr>

`Concepts used:`
- *List, Tuple, Dictionary*
- *Random number generation*
- *Iterations, conditional statements and functions*