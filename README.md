# PixelPulse

# PixelPulse Game

## Description
PixelPulse is an interactive web game where a green square moves around a grid. The objective is to navigate and interact with different colored squares that change over time. As you play, squares change to colors like blue, yellow, pink, red, orange, and brown based on specific actions.

## Features
- **Green Square**: The starting position and main object you control.
- **Colored Squares**: Each color represents a specific action. For example:
  - **Yellow**: Changes to blue and moves up.
  - **Blue**: Changes to yellow and moves down.
  - **Pink**: The square teleports to a random position.
  - **Red**: Creates orange squares around it and teleports the green square.
  - **Orange**: Creates surrounding orange squares.
  - **Brown**: All white squares turn brown after 5 minutes of play.

## Gameplay Mechanics
- The square moves automatically at the start and changes based on the colored squares it encounters.
- There is a 25% chance that a random square will turn pink, causing the green square to teleport to a new position.
- After 10 pink squares are created, a red square is generated.
- When the green square hits a red square, surrounding squares turn orange, and the green square teleports to a new position.
- After 5 minutes of play, all white squares turn brown, and the game stops if there are no more white squares left.

## How to Play
1. Open the `index.html` file in your web browser.
2. The game starts automatically, and the green square begins moving.
3. Interact with the squares and watch them change over time.

## Warning
**This code is written for a personal project and should not be copied or used without permission. Any form of distribution or further use without proper attribution is not allowed.**

## License
This code is subject to the terms mentioned in the above warning. Use it only for personal learning or development. All rights are reserved by the original author.
