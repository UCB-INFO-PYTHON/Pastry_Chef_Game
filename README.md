# Pastry_Chef_Game
***
Lorrel Plimier

Berkeley MIDS – Python w200 – Project 1 –  Fall, 2018

Lorrel.plimier@ischool.berkeley.edu
***
The general idea for this game is that the player is attempting to advance from Novice to Master Pastry Chef by taking cake orders and successfully completing them. The player moves between rooms and completes tasks in a particular sequence to successfully fulfill a cake or cookie order. Points are awarded for success and subtracted for mistakes.

This is mostly a simple memory game. The player needs to remember the order in an effort to make fewer mistakes and avoid losing points. There is also an order of operations component to the game, but once a player completes one or two orders, this part should be pretty clear. 

**To run the game**, just execute the Pastry_Chef.py file with the egg.py file in the same folder. You should be able to easily play this game without knowing anything about it. Everything you need to know is given to you as you play (though you might lose some points along the way as you learn.) Some of the more entertaining text in the game is through asking for help and trying to get orders in the “office” or “storefront.” One thing to note: this game works perfectly at my Windows command prompt. I haven’t tested it with Mac or Linux. The time delay (sleep function) and clear screen function do not work at my Git Bash prompt. This doesn’t affect the actual game play but it does affect the aesthetics of the game, causes time delays that are bunched together (you need to wait several seconds for text to appear at all,) and makes it less pleasing to read the text.

My kids recommended that I add an **Easter egg** to the game, so I have. It should be pretty easy to find if you look at the code (especially given my special “egg” module,) but you might not accidentally stumble upon it while playing the game. So, if you’d like to see it, keep taking eggs from the refrigerator. The clear screen and sleep functions must work properly in order to appreciate the Easter egg. (It doesn’t work for me at the Git Bash prompt, only the Windows command prompt.) The egg’s ascii animation is basically like a flip book. I’ve included the .txt file that has my individual animations, in case you want to take a look at them, since it is difficult to visualize them when they are in lists of strings with double back slashes.

Good luck and have fun!
