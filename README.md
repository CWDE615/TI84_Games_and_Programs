# TI84_Games_and_Programs
In this directory there are a collection of games and useful programs for the TI84 that I've written since high school and recently started maintaining.

Below is a list of directories and the programs within them:
## 1. Misc (Miscellaneous Games)
|Game|Description|
|:---|:----------|
|Guess|This single file program is a simple guessing game in which one number 1 through 1000 is generated and the user is asked to guess it while being told whether their guesses are too low or too high.|
## 2. Rules84 (A Battle Royale game for the TI84)
Program|Description|Called In|
:------|:----------|:--------|
Rules84|An entry point for the program. Also manages the overworld and movement of control to Loot and Rush|Entry Program
Loot   |Manages the looting of verious places throughout the overworld|Rules84
Rush   |Manages confrontations between the player and enemies which may happen randomly through Rules84 or Loot|Rules84 and Loot
## 3. Utility (Utility Programs)
|Program|Description|
|:---|:----------|
|R|A program I wrote recently to calculate the correlation coefficient R and the coefficient of determination R^2 from data in lists 1 and 2 or from parameters passed by the user|
## 4. Wanderer (A Rogue-Like RPG for the TI84)
Program|Description|Called In|
:------|:----------|:--------|
Wanderer|Handles entrance into other programs through overworld as well as locations in game|Entry Program
Dungeon|Handles dungeon functionality|Wanderer
Battle|Handles battling enemies and the final boss (the Necromancer)|Wanderer and Dungeon
Stats|Displays the player's stats|Wanderer and Battle
