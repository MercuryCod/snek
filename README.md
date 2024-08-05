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

## Project Details

This project is based on UCB CS61C project 1. For more detailed instructions and information, you can check their [official project website](https://cs61c.org/fa19/proj1/).

## Getting Started from scratch

To get started, first create your own Git repository and enter the following commands in your terminal:

```sh
git remote add starter https://github.com/61c-teach/su24-proj1-starter.git
git pull starter main
```

## Running the Project

To run the already built project, you can first clone this project onto your repo and then enter the following commands in your terminal:

```sh
make interactive-snake
./interactive-snake
```

Use the `wasd` keys to control your snake!

To speed up or slow down the game, you can run:

```sh
./interactive-snake -d 0.5
```

Replace `0.5` with the number of seconds between time steps. During the game, you can also press `]` to move faster and `[` to move slower.

## How to Play

1. **Movement:** Use `wasd` keys to control the direction of your snake.
2. **Speed Control:** Adjust the speed of the game using the `-d` option or the `]` and `[` keys during gameplay.
3. **Objective:** Navigate your snake to eat fruits (`*`) and grow longer while avoiding collisions with walls (`#`) and other snakes.

## References

For detailed instructions and more information, refer to the [official project website](https://cs61c.org/fa19/proj1/).

