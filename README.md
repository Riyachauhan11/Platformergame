Here’s the updated `README.md` with content only up to the "How to Play" section:

---

# 2D Platformer Adventure Game

This is a **tile-based, 2D platformer adventure** game where the player navigates through levels to reach the exit door while avoiding hazards like lava pits and enemy sprites. The game becomes progressively challenging with more complex layouts and enemies.

## Game Overview

- **Genre**: 2D Platformer
- **Gameplay**: Navigate the character through each level by jumping on platforms and avoiding hazards. Instant death occurs if the player falls into a lava pit or touches an enemy.
- **Difficulty**: The difficulty increases as the levels progress, with more obstacles and hazards to overcome.

## Project Structure

```
|-- assets/
|   |-- sprites/           # Character and enemy sprites
|   |-- tilesets/          # Tile-based environment textures
|   |-- sounds/            # Background music and sound effects
|
|-- src/
|   |-- main_game.py       # The main game logic file
|   |-- level_editor.py    # A level editor for creating new levels
|
|-- levels/
|   |-- level1.json        # Sample level layout
|   |-- level2.json        # Additional levels
|
|-- dist/
|   |-- game.zip           # Contains the playable game executable (.exe)
```

## How to Play

1. **Start the Game**:
   - Extract the `game.zip` file located in the `dist` folder.
   - Run the `.exe` file to launch the game.

2. **Controls**:
   - `Arrow keys` to move.
   - `Spacebar` to jump.
   - Avoid hazards like lava and enemies to survive and reach the exit.

3. **Game Goal**:
   - Reach the exit door on each level without dying.

---

This version should fit your needs!
