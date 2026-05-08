
## Changes Made

### 1. Moving Food
The food was modified so it can move randomly one step at a time during the game.

### Characteristics
- Added random movement logic for the food.
- Prevented the food from leaving the game window boundaries.
- The food position updates automatically while the game is running.

---------------------

### 2. Random Snake and Food Colors
The snake and the food now receive random colors every time the game starts.

#### Characteristics
- Created a list of 5 possible colors:
  - blue
  - green
  - yellow
  - purple
  - orange
- Red was excluded from the random color list.
- Used random selection to assign:
  - one color to the snake
  - a different color to the food
  - a different color when you loose

---------------------
