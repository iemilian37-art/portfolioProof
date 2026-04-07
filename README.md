# portfolioProof
A proof of that i have made my game

the game is a simple game i stopped working on a decent time ago. It was inspired by slap battles and i wanted to make one using roblox's old gears.

for the datastore it's a simple system which makes it so any folder you put into the plr folder inside the script will add the folders into the player and save the values. it does this by creating a loop and looping through all folders inside of the plr folder and it also loops all values inside of each folder.

for the round system's roundmanager. it basically detects how many players are in the game and if there are not enough players then the timer is set really high and you must wait until enough players join. once enough players join it picks a random map in server storage and puts it into workspace. there is also a formatting function which simply just makes it so 126 seconds would say 2 minutes 6 seconds instead
the teleport manager just checks the teleport folder inside of the map that is loaded from the roundmanager and basically just chooses a random part inside of that folder and teleports the player to it whenever it's ready
the toolgiver destroys all previous tools in your backpack whenever needed and detects what tool the player has equipped and grants that tool to the player.
