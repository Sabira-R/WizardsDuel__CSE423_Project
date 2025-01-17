# Wizard's Duel Game

[Wizard's Duel](https://github.com/Sabira-R/WizardsDuel__CSE423_Project/blob/main/Final%20one) is a 2D action game where players control a wizard battling against flying dementors. Use spells to defeat the enemies, dodge their curses, and aim for victory. The game is built using Python with the PyOpenGL library for 2D graphics.

---

## Features

- **Wizard Control**: Move your wizard to aim and shoot spells at the dementors.
- **Spell Casting**: Fire various spells, each with unique effects, to defeat enemies.
- **Dynamic Difficulty**: Game becomes more challenging as your score increases.
- **Dementors as Enemies**: Multiple dementors with individual attributes like speed and health.
- **Themes**: Choose your house color (Gryffindor, Slytherin, Hufflepuff, or Ravenclaw).
- **Score Tracking**: Compete with yourself for the highest score.
- **Game Management**: Pause, restart, or exit the game easily.

---

## Controls

### Mouse Controls:
- **Theme Selection**: Left-click on the house color squares (red, green, yellow, or blue) to choose your theme.
- **Pause/Play Game**: Click the play/pause button to toggle between starting and pausing the game.
- **Restart Game**: Click the restart button to reset the game to its initial state.
- **Exit Game**: Click the exit button to quit the game.

### Keyboard Controls:
- **Movement**: 
  - Press `A` or the **Left Arrow Key** to move the wizard left.
  - Press `D` or the **Right Arrow Key** to move the wizard right.
- **Pause Game**: Press the **Spacebar** to toggle pause.

---

## How to Play

1. **Setup**: 
   - Run the game using the command:
     ```bash
     python <filename>.py
     ```
   - Ensure your system meets the requirements listed below.

2. **Gameplay**:
   - **Choose a Theme**: Select a house by clicking on one of the colored squares.
   - **Attack Dementors**: Use spells to defeat the dementors while avoiding their curses.
   - **Score Points**: Destroy dementors to increase your score.
   - **Stay Alive**: Dodge incoming curses and manage your lives.

3. **Winning Condition**:
   - Defeat all dementors to win the game.

4. **Game Over**:
   - The game ends when you lose all your lives.

---

## Gameplay Elements

- **Wizard**: Your character, equipped with movement and spell-casting abilities.
- **Dementors**: Enemies with unique movement patterns, health, and attacks.
- **Spells**: Projectiles you control to attack enemies.
- **Curses**: Obstacles launched by dementors. Avoid them to survive.
- **Lives**: Start with 3 lives; losing all results in a game over.
- **Levels**: The game progresses through levels, increasing difficulty with faster curses and smarter enemies.

---

## Requirements

- Python 3.x
- PyOpenGL
- GLUT

### Installation:
Install the necessary dependencies with:
```bash
pip install PyOpenGL PyOpenGL_accelerate
