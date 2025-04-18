
 # Dungeon Adventure Game

## Overview

Welcome to the Dungeon Adventure game! Embark on an exciting dungeon-crawling adventure, fight monsters, explore treasure-filled rooms, avoid traps, and more. The game is designed to be played in a terminal environment where you control the Hero as they navigate through various dungeon levels.

The game includes features like saving and loading progress, a dynamic level generation system, and turn-based combat with multiple special rooms and enemies.

## Features

- **Hero Class**: Manage the hero's stats, inventory, level, and abilities.
- **Special Rooms**: Encounter different types of rooms, including traps, treasure, battles, and exits.
- **Turn-Based Combat**: Fight against monsters and bosses with different strategies.
- **Level Progression**: The game increases in difficulty as you progress through levels.
- **Save/Load Game**: Save your progress and load your saved game.


## Usage

1. Run the game by executing the following command:

    ```bash
    python dungeon_adventure.py
    ```

2. Follow the prompts in the terminal to control the Hero and interact with the game world. You'll be given options to move, use items, fight monsters, and more.

3. Use the following controls in the game:
   - `1` to move your character (choose a direction: north, south, east, west).
   - `2` to check your hero's stats.
   - `3` to view and manage your inventory.
   - `4` to use items from your inventory.
   - `5` to see the dungeon map.
   - `6` to save your progress.
   - `7` to load a previously saved game.
   - `8` to quit the game.

## Game Flow

- **Levels**: The game consists of multiple dungeon levels. Each level has its own grid with special rooms that may contain traps, treasure, or battles.
- **Combat**: Fight against monsters using turn-based mechanics. Use actions such as attack, defend, or use items from your inventory.
- **Saving and Loading**: Your progress is automatically saved in a file called `savegame.json`. A hash of the save file is also stored to ensure data integrity. You can load your progress at any time.


