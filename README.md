# Super Mario Bros. 2 Randomizer
by MaCobra52

This is a randomizer for Super Mario Bros 2 (US) that includes the following core options:

- **Character Randomizer** - modifies the game so that in each level you are locked into selecting one character chosen at random (they are automatically highlighted and you cannot use left/right to change them). Additionally, the attributes/stats of all four characters can also be randomized (speed, jumping, floating ability, etc.)

- **Level Randomizer** - Shuffles the level order (except for 7-2, which is always last) and optionally the transitions within each level, including where doors and vines take you. Additional options are also included to customize the level randomization, modify warp functionality, randomize most plants that you pull from the ground, randomize how often stars, hearts, and stopwatches appear, and randomize the background and sprite colors.

- **Enemy/Boss Randomizer** - Randomizes most ground enemies, Pansers, Sparks, the small jars that generate enemies, where Phanto appears, Birdos (type and HP), Birdo pattern, the HP of major bosses, and boss difficulty

Additionally, many QoL features have been implemented and are customizable, such as the ability to set your starting lives and health, unlimited continues, faster digging, alternative music from the Prototype version of SMB2, and more!


### First Time Instructions:

Ensure that you have Java 8 or later installed on your machine prior to running. If needed you can download from the link below:
https://www.java.com/en/

1. Double-click the exe or jar to start the randomizer.
2. Select the base SMB2U ROM (PRG0 or PRG1/Rev A) that you would like to use along with the output directory of the randomized ROM.
3. Enter a number for the seed, or use the one provided.
4. If you wish to adjust any of the settings, adjust the appropriate options on each tab. You can randomize character choice, character attributes, levels, plants, background colors, enemies, Birdo, boss hp, set starting lives, continues, health, change character colors, and more! (Hover over each option for additional details)
5. click 'Generate!'

At this point you can close the randomizer and play! The randomizer will remember the previous files, directories, and settings chosen, so in the future all you need to do is adjust the seed (if desired) and click 'Generate!'


### Notes:

- The base ROM selected must be a clean PRG0 or PRG1/Rev A SMB2U ROM.

- If you are planning a race, be sure that all participants enter the same seed and flags to generate the same randomization. Additionally a hash will be displayed on the title screen (in place of the copyright) and included in the file name to confirm that everything matches. With the exception of the character color and music options present, hashes will NOT match if a different seed or different settings are chosen.

- In the randomizer, options in Red are generally not recommended for beginners. Options in Purple can be freely adjusted without affecting the resulting Flags/Hash.

- With enemy randomization, there may be difficult/unfair scenarios that can occur, but care has been taken where necessary (and possible) to prevent softlocks and being forced to take damage to progress. Additionally a Speedrun Friendly option exists that does not randomize certain additional enemies that are used during a typical speedrun of the game.

- Extra care has been taken when randomizing levels transitions to ensure no softlocks can occur, but some results may be a bit on the challenging side. Be sure you have tried all possibilities and note the following:
  - 3-1: This is the only level that has an odd number of transitions, allowing two transitions to link to the same destination (normally used to exit the area with the warp)
  - 3-3: Sometimes you may need to fall down the tower sections with the key in order to get to the lock (since you cannot climb chains with the key)
  - 7-2: The door transition going from the Birdo holding the key to the room with the lock is mostly unchanged (for now)


### Known Oddities:

- Your health is still capped at 4 HP regardless of which Starting Health option you pick. Attempting to go above 4 HP (by collecting enough Mushrooms) will result in the health bar becoming glitched until you either beat the current level or game over.

- Certain 'Wrong Warp' speedrun techniques may have unpredictable results when attempted due to the nature of randomizer, especially with level transitions randomized.

- Sometimes a Tweeter or Snifit may emerge from an Ostro when separated instead of a Shyguy like normal. This is a minor side effect from randomizing Small Jars.


### Vanilla Glitches to be Aware of:

- If you pick up a plant containing a Bob-omb while the screen is shaking from throwing a POW block, the Bob-omb will simply fall off the screen without exploding, but it WILL explode without warning in the next room you transition to, resulting in unavoidable damage (unless you are climbing a vine). To avoid this it is recommended that you do not pick up plants during the shaking effect if the plant's contents are unknown.


### Special Thanks To: 

- CurtsNewBrand for all of the inital testing for this idea and giving me the drive to see it through.

- Xkeeper and kmck for their amazing work on the SMB2 disassembly, which none of this would be possible without.

- SpiderDave for permission to integrate some of his SMB2 improvements into the randomizer.

### Discord:

For the latest developments, including Beta releases, be sure to check out the Super Mario Bros. 2 Randomizer discord (shared with pepperpow's Door Randomizer):
https://discord.gg/gNXANyV

### Enjoy!

### Screenshots

![smb2r1](https://user-images.githubusercontent.com/24445539/221449562-2d1344a9-6920-4e40-a627-554400e75d43.png)
![smb2r2](https://user-images.githubusercontent.com/24445539/221449600-d21e77b6-6ba0-4e2f-b3ed-83a83a925c4d.png)
![smb2r3](https://user-images.githubusercontent.com/24445539/221449627-ab38caff-9bf2-41c9-963c-96cb0dba9914.png)
![smb2r4](https://user-images.githubusercontent.com/24445539/221449634-7cf1e418-41bb-4db4-8567-71b4c6cf9375.png)
![smb2r5](https://user-images.githubusercontent.com/24445539/221449645-da8b2c6f-33d2-4f12-b73b-8554498d93e0.png)
