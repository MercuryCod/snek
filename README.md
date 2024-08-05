# Snakes

This project implements a classic Snake game, represented by a grid of characters. The grid contains walls, fruits, and one or more snakes, each with its own direction and behavior.

## Game Description

The game features:
- Walls (`#`)
- Empty spaces (space character)
- Fruits (`*`)
- Snake tails (`wasd`)
- Snake bodies (`^<v>`)
- Snake heads (`WASD`)
- Dead snake heads (`x`)

Each snake moves according to the direction indicated by its head. The game follows specific rules for movement, collision, and fruit consumption.

## Gameplay Rules

1. Snakes move one step in the direction of their heads.
2. Collisions with walls or other snakes result in death (`x`).
3. Consuming a fruit (`*`) causes the snake to grow and a new fruit to appear.

## Snake Numbering

Snakes are numbered based on the position of their tails in the initial game state, from top to bottom, left to right. This numbering remains constant throughout the game.

## Game Board

The game board is a grid of characters, which can vary in size and shape. The board is enclosed by walls, ensuring snakes cannot move infinitely far in any direction.

## Project Structure

- `state.h`: Defines the `game_state_t` and `snake_t` structs.
- `state.c`, `snake.c`, `custom_tests.c`: Implement the game logic and tests.

This project is based on UCB CS61C project 1, you can check their [official project website](https://cs61c.org/fa19/proj1/)](https://cs61c.org/su24/projects/proj1/) to get more guidance.

To get start, you can first create your own git repository and enter the following on your terminal :

```sh
git remote add starter https://github.com/61c-teach/su24-proj1-starter.git
git pull starter main
```

