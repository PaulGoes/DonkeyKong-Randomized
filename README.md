# Donkey Kong Arcade - Randomized Edition

This is the Donkey Kong - Randomized Edition rom-hack for the arcade version of Donkey Kong.

The idea is to have a Donkey Kong version that selects each board randomly: a random level (between 1 and 5) and a random screen (barrels, pies, springs, rivets). 

![DKRND Title Screen](https://github.com/PaulGoes/DonkeyKong-Randomized/blob/master/Title%20Screen.jpg?raw=true)

The selection of each board is random without knowing what it selected before. It is even possible that you have the same board again after completing it.

To get a more interesting randomization for skilled Donkey kong Players, the randomization doesn't distribute the levels and screens evenly. The used randomization algorithm results in the following distribution:

| Level   | Probability  |
| ------- |:------------:|
| 01      | 3½ %         |
| 02      |  9 %         |
| 03      | 25 %         |
| 04      | 25 %         |
| 05      | 37½ %        |

| Screen  | Probability  |
| ------- |:------------:|
| Barrels | 50 %         |
| Pies    | 12½ %         |
| Springs | 25 %        |
| Rivets  | 12½ %        |

The randomly selected board is shown in the level progress screen:

![DKC Level Progress Screen](https://github.com/PaulGoes/DonkeyKong-Randomized/blob/master/Do%20You%20Feel%20Lucky.jpg?raw=true)

- The Level is indicated in the upper right corner: L=01, L=02, L=03, L=04 and L=05.
- The screen is indicated by the number of Goofy Kongs: 1=Barrels, 2=Pies, 3=Springs, 4=Rivets.
- So the random selected board of the above screen is Springs L=04.
- The game doesn't select boards that are not in the original game: Pies L=01, Springs L=01 and Pies L=02.

Normally the overall progress in the game is shown by the level. But in this game that is of no use because the level is randomly chosen between 1 and 5. To show the progress a randomization count is displayed that counts the number of performed randomizations.

On most other emulators (e.g. WolfMame) you can play this game by replacing the original dkong.zip by this Reverse version of the dkong.zip. You have to start the emulator without checksum checking (in WolfMame by starting it from the command line and specifying the romname).
