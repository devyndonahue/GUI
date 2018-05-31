# GUI
I created an engine for generating pseudorandom explorable worlds, containing a random number of rooms and hallways at random places with random size in each world. A seed must be inserted and each unique seed is a different world.
Created two methods of starting: playWithInputString(String s) and playWithKeyboard()
Used a tile rendering engine that took in a 2d array, and I made sure it was in bounds and then added halls, rooms, objects, floors, and walls.
Created a player that moves around the world using the W,A,S,D keys
Created a Heads Up Display, that when hovering over a part on the world it outlines what is under your mouse.
Created a menu with different options: Background information, choice of player, a load previous game option.
When in the game, the player can press Q to quit and save the game.
