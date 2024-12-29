# 2024 Fall NTUCSIE Intro to Computer Final Project

## Game: Gate Dash
A simple game made with programming language Jack, following nand2tetris.org course.

## Usage
Download the software package from [nand2tetris](https://www.nand2tetris.org/software). Also download all the files from `vm/` of this repo to a single local directory of your choice.

Then, in `nand2tetris/tool/VMEmulator`, choose "Load Program", and select the entire directory where the `*.vm` reside. Finally, scroll "Speed" to fastest, switch "Animate" to "No Animation", and click "Run".

## How to Play
- **Rule**: When the player encounters a gate, its Boolean value will change accordingly. The score increases when the player’s Boolean value changes from 0 to 1 (positive edge). Hitting on an obstacle ends the game. The game levels up every 5 points scored, up to the maximum level. Try to score as many as you can!
- **Controls**: Press SPACE to start, pause, or restart the game. Press UP or DOWN to move the player.

## Demo
[Click here to see the gameplay and demo video](https://youtu.be/2IyrNC_a1FI)

## Acknowledgements
https://github.com/N2Tstud3nt/nand2tetris-project09-Flappy-Bird (for Linear Congruential Generator implementation in Jack language)

https://github.com/ErikUmble/nand2tetris/tree/main/DinoAdventure (for ideas of drawing horizontally moving objects)

https://github.com/ErikUmble/JackBitmapEditor (for providing an useful drawing tool)