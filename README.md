# ICS3U-Battleship-Game

This program is a fully playable version of the board game Battleship made in Java. Made by Eren Sulutas. 

To do list:  
- Replayablilty? Leaderboard?
- Un-comment the ship 


Smarter UI: 
- Have the coordinates of the surrounding cells
- If a ship is hit but not sunk, set boolean a to true 
- When the CPU makes a choice for the next shot, check if bool a is true 
- If false, proceed with random coordinates
- If true, make a random number from 0-3 to determine which of the surrounding cells to shoot at
- If the cell is valid and unoccupied, set boolean a to false (right before it checks for sunken ships
- Make sure the surrounding entry does not go out of bounds 
