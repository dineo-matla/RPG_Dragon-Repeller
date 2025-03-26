# RPG Game

## Overview
This is a simple role-playing game (RPG) built using JavaScript, HTML, and CSS. Players can explore different locations, track their stats, buy weapons, and fight monsters. The game is text-based, but it provides an engaging experience through interactive gameplay mechanics.

## Features
- **Stat Tracking:** Players can monitor their health, gold, and attack power.
- **Exploration:** Different locations, including the town square, store, and cave, allow for varied gameplay.
- **Store System:** Players can buy weapons to increase their attack power.
- **Combat System:** Players can battle monsters and earn rewards for victories.
- **Dynamic Data Structure:** The game uses an object-based data structure to manage locations and gameplay elements.

## How It Works
1. **Game Initialization:**
   - The game starts in the town square, where players can decide what to do next.
   
2. **Exploring Locations:**
   - Players can move between the **town square**, **store**, and **cave** using buttons.
   - Each location offers different interactions.
   
3. **Buying Weapons:**
   - In the store, players can buy weapons using gold.
   - Weapons increase attack power for battles.

4. **Fighting Monsters:**
   - Players can enter the cave to fight monsters.
   - Battles are turn-based, where the player and monster take turns attacking.
   - Winning grants rewards, while losing affects health.

## Technologies Used
- **JavaScript** – Core logic for handling gameplay.
- **HTML** – Structure of the game interface.
- **CSS** – Basic styling to enhance the visuals.

## Challenges and How I Overcame Them
### 1. **Managing Game State Dynamically**
   **Challenge:** Keeping track of player stats, inventory, and current location without making the code too complex.
   
   **Solution:** Implemented an object-oriented approach, storing game data in objects. Used a structured data model for locations and inventory.


### 2. **Implementing a Turn-Based Combat System**
   **Challenge:** Ensuring fair combat where both the player and enemy take turns attacking.
   
   **Solution:** Created a function that alternates between player and monster attacks using a sequence of function calls and condition checks.

### 4. **Preventing Negative Stats and Balancing the Game**
   **Challenge:** Players sometimes ended up with negative health or gold due to miscalculations.
   
   **Solution:** Implemented logic to prevent stats from going below zero and adjusted reward scaling for better balance.

## Future Improvements
- Adding **visual elements** like sprites for the player and monsters.
- Implementing **sound effects and background music** for better immersion.
- Creating a **more complex combat system** with skills and abilities.
- Expanding the **game world** with new locations and questlines.

## How to Play
1. Open **live site** in your browser.
2. Follow on-screen instructions to explore, buy weapons, and fight monsters.
3. Try to increase your stats and defeat stronger enemies!

Enjoy the adventure!

