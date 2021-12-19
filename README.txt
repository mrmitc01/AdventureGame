AdventureGame

This code is used to create a small game that allows the player to explore a world  made up of “rooms” 
(which may be outdoor locations) that may contain items that can be “taken” and “dropped”. The player 
can move room to room by taking an exit, denoted by “north”, “south”, “east” or “west”. The player must 
discover a quest (task/mission) to perform which involves finding and taking certain objects and dropping 
them in a “win room”. Each room and item has a short description and a long description. Each room may 
have a list of 0 to 5 items (the room’s inventory) and should have one to four exits (north/south/east/west). There is also a player inventory consisting of 0 to 5 items. To make the game flexible for non-programmers, 
the description of the rooms, its objects, and the details of how to win, are stored in a text file that can 
be written by anyone who knows the rules of writing the file.

The purposes of each of the following files are stated below:


gameutils.cpp -  to provide various functions that will be useful throughout the program

gameutils.h -  to provide constant and structure declarations and function prototypes for the game

MiniMUDGame.cpp - to implement a Mini-MUD game that allows the player to explore a world made up of 
                  rooms (which may be outdoor locations) that may contain items that can be taken and 
                  dropped. The player can move room to room by taking an exit, denoted by north, south, 
                  east or west. The player must discover a quest (task/mission) to perform which involves 
                  finding and taking certain objects and dropping them in a win room.

cat.txt - input file for cat game        

dog.txt - input file for dog game

lunch.txt - input file for lunch game


Compile the source code by typing the following at the prompt $:
$ g++ gameutils.cpp MiniMUDGame.cpp -o MiniMUDGame 

Code is available upon request
