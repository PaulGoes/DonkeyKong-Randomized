# Donkey Kong Arcade - Randomized Edition

This is the Donkey Kong - Randomized Edition rom-hack for the arcade version of Donkey Kong.

The idea is to have a Donkey Kong version that selects each board randomly: a random level (between 1 and 5) and a random screen (barrels, pies, springs, rivets). 

![DKRND Title Screen]()

The selection of each board is random without knowing what it selected before. It is even possible that you have the same board repeating immediately.
To give an impression this is the order of played boards of one of the played test runs:

Rivets L2 - Pies L3 - Barrels L5 - Springs L5 - Rivets L3 - Barrels L2 - Springs L5 - Pies L3 - Rivets L5 - Barrels L3 - Pies L5 - Barrels L5 - Pies L3 - Pies L5 - Springs L5 - Barrels L2 - Pies L4 - Springs L5 - Springs L3 - Rivets L2 - Rivets L3 - Springs L3.

The randomly selected board is shown in the level progress screen:

![DKC Level Progress Screen]()

The Level is indicated in the upper right corner: L=1, L=2, L=3, L=4 and L=5.
The screen is indicated by the number of Goofy Kongs: 1=Barrels, 2=Pies, 3=Springs, 4=Rivets.

Normally the overall progress in the game is shown by the level. But in this game that is of no use because the level is randomly chosen between 1 and 5. To show the progress a randomization count is displayed that counts the number of performed randomizations.

Because the random level is between 1 and 5 there will never be a Kill Screen (normally at level L=22). So the really skilled player might keep on playing and playing. To accomodate for very high scores, the score also displays the millions.