# SMB2-Randomizer
by MaCobra52

This is a randomizer for Super Mario Bros 2 (US) that includes the following core options:

- **Character Randomizer** - modifies the game so that in each level you are locked into selecting one character chosen at random. The character is automatically highlighted and you cannot use left/right to change them. Additionaly character attributes/stats can also be randomized (speed, jumping, floating ability, etc.)

- **Level Randomizer** - Shuffles the level order (except for 7-2, which is always last). Additional options are also included to customize the level randomization, modify warp functionality, randomize most plants that you pull from the ground, randomize how often stars and hearts appear, and randomize the background colors.

- **Enemy/Boss Randomizer** - Randomizes most ground enemies, Pansers, Sparks, the small jars that generate enemies, Birdos (type and HP), Birdo pattern, and the HP of major bosses.


### First Time Instructions:

Ensure that you have Java 8 or later installed on your machine prior to running. If needed you can download from the link below:
https://www.java.com/en/

1. Double-click the exe or jar to start the randomizer.
2. Select the base SMB2U ROM (PRG0 or PRG1/Rev A) that you would like to use along with the output directory of the randomized ROM.
3. Enter a number for the seed, or use the one provided.
4. If you wish to adjust any of the settings, adjust the appropriate options on each tab. You can randomize character choice, character attributes, levels, plants, background colors, enemies, Birdo, boss hp, set starting lives, continues, health, change character colors, and more!
5. click 'Generate!'

At this point you can close the randomizer and play! The randomizer will remember the previous files, directories, and settings chosen, so in the future all you need to do is adjust the seed (if desired) and click 'Generate!'


### Notes:

- The base ROM selected must be a clean PRG0 or PRG1/Rev A SMB2U ROM.

- If you are planning a race, be sure that all participants enter the same seed and flags to generate the same randomization. Additionally a hash will be displayed on the title screen (in place of the copyright) and included in the file name to confirm that everything matches. With the exception of the character color and music options present, hashes will NOT match if a different seed or different settings are chosen.

- With enemy randomization, there may be difficult/unfair scenarios that can occur, but care has been taken where necessary to prevent softlocks and being forced to take damage to progress. Additionally a Speedrun Friendly option exists that does not randomize certain additional enemies that are used during a typical speedrun of the game.


### Known Oddities:

- Your health is still capped at 4 HP regardless of which Starting Health option you pick. Attempting to go above 4 HP (by collecting enough Mushrooms) will result in the health bar becoming glitched until you either beat the current level or game over.

- Certain 'Wrong Warp' speedrun techniques may have unpredictable results when attempted due to the nature of randomizer (the popular ones used in 1-1, 1-3, and 3-3 ARE confirmed to work the same as in vanilla however)

- Sometimes a Tweeter or Snifit may emerge from an Ostro when separated instead of a Shyguy like normal. This is a minor side effect from randomizing Small Jars.


### Vanilla Glitches to be Aware of:

- If you pick up a plant containing a Bob-omb while the screen is shaking from throwing a POW block, the Bob-omb will simply fall off the screen without exploding, but it WILL explode without warning in the next room you transition to, resulting in unavoidable damage (unless you are climbing a vine). To avoid this it is recommended that you do not pick up plants during the shaking effect if the plant's contents are unknown.


### Special Thanks To: 

- CurtsNewBrand for all of the inital testing for this idea and giving me the drive to see it through.

- Xkeeper for their amazing work on the SMB2 disassembly, which none of this would be possible without.

- SpiderDave for permission to integrate some of his SMB2 improvements into the randomizer.

### Enjoy!
