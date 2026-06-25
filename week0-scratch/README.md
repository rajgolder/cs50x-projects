# Dragon Battle - Scratch Game

#### Video Demo:
(I will add soon)

#### Description:

Dragon Battle is a Scratch-based action game created for CS50x Week 0. 
The player controls a warrior character and fights against a dragon boss using sword attacks.

The goal of the game is to defeat the dragon before the player's health reaches zero.

## How to Play

- Use the **Left Arrow** key to move left.
- Use the **Right Arrow** key to move right.
- Press the **Space Bar** to attack with your sword.
- Hit the dragon multiple times to reduce its health.
- Avoid taking too much damage from the dragon.

The game ends when:
- The dragon's health reaches 0 → You win.
- The player's health reaches 0 → Game over.

## Features

- Player movement system
- Attack system using Scratch clones
- Boss battle mechanics
- Health system for both player and dragon
- Collision detection between attacks and enemies
- Damage system using custom blocks
- Win and lose conditions
- Basic animations and sound effects

## Design Choices

I created this project as a simple boss fight game inspired by action RPG games.

The game uses:
- Variables to track player and boss health
- Broadcast messages for communication between sprites
- Cloning to create sword attacks
- Custom blocks to organize damage logic
- Conditional statements to control game states

One challenge was preventing the player from continuing to attack after the dragon was defeated. I solved this by adding a game state variable that disables actions after the battle ends.

## Files

- `Dragon Battle (scratch Game).sb3` - The Scratch project file

## Author

Created by:
Raj

CS50x Week 0 - Scratch