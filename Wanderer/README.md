# Wanderer
A Rogue-Like RPG for the TI84 calculator.

## Programs Used
Program|Description|Called In|
:------|:----------|:--------|
Wanderer|Handles entrance into other programs through overworld as well as locations in game|Entry Program
Dungeon|Handles dungeon functionality|Wanderer
Battle|Handles battling enemies and the final boss (the Necromancer)|Wanderer and Dungeon
Stats|Displays the player's stats|Wanderer and Battle

## Variables Used
Variable|Use|
:-------|:--|
T|Holds a menu option in town and is used as a flag to signal the Necromancer fight in the Battle program|
P|Tracks which dungeon quest, if any, the player is on|
Q|Used to hold a randomly generated number used to determine what quest the player will go on when they ask for one in town
S|The player's Strength stat
L|The player's Luck stat
A|The player's Agility stat
I|The player's Intelligence stat
N|The player's Intimidation stat
H|Holds the player's current health
E|Holds enemies' current health
G|Holds the player's current gold
F|Tracks the player's Attack Skill (whether or not they know the Advanced Strike)
K|Tracks the player's Magic Skill (whether or not they know Flames or Earthquake)
J|Tracks the Renown of the player (boosted by fighting battles or by doing certain quests)
Z|A flag for whether the player is under the effect of Necrosis (only possible in the battle with the Necromancer)
R|Holds user input in the Battle program and various randomly generated numbers throughout the game
X|The player's position on the X-axis of the overworld
Y|The player's position on the Y-axis of the overworld
V|Holds the random position on the X-axis of the Monster in the overworld
W|Holds the random position on the Y-axis of the Monster in the overworld
