# Rules84
An implementation of the mobile Battle Royale style of games that were ubiquidous during my high school years.

## Programs Used
Program|Description|Called In|
:------|:----------|:--------|
Rules84|An entry point for the program. Also manages the overworld and movement of control to Loot and Rush|Entry Program
Loot   |Manages the looting of verious places throughout the overworld|Rules84
Rush   |Manages confrontations between the player and enemies which may happen randomly through Rules84 or Loot|Rules84 and Loot

## Variables Used
Variable|Use|
:-------|:--|
M       |Stores the X-axis value of the map the player is on|
N       |Stores the Y-axis value of the map the player is on|
P       |The number of enemies to be eliminated|
B       |The number of enemies eliminated by the player|
H       |The player's current health|
D       |The Amount of damage the player does while shooting enemies in the Rush program|
X       |The X position of the player on the current map|
Y       |The Y position of the player on the current map and the Y position of the players bullet in the Rush program|
A       |The player's last input while they are in the overworld|
C       |A randomly generated number 1 through 16 that is regenerated following each step the player takes. If it is 16 after they take a step, they encounter an enemy.|
L       |The seed used to generate the loot for the player in the Loot program|
W       |The Y coordinate of enemies' bullets in the Rush program|
V       |The vitality of the enemy in the Rush program|
E       |The health of the enemy in the Rush program|
R       |Randomly generated number to generate loot in the Loot program|

