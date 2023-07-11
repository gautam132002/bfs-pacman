# Pacman Game with Breadth First Search Algorithm

This is a simple Pacman game implementation that demonstrates the Breadth First Search (BFS) algorithm. The game features a stationary maze with two stationary enemies and one,two food objects. The objective is to use BFS to move the main character (Pacman) towards the food objects without contacting the enemies. 

## Game Rules

- The maze (playground) is always stationary.
- There are two stationary enemies and two food objects.
- The main character (Pacman) is a moving character.
- The enemies and food objects load at random positions each time the game starts.
- In `bfs.py`, the goal is to eat two food objects that appear on the screen, and then the game terminates.
- In `main.py`, the game runs in an infinite loop until there is no path remaining to reach the food. Pacman eats the food, and a new food item generates after that. This process keeps going indefinitely.

## Program Files

The project consists of two program files:

1. `bfs.py`: This file contains the implementation of the Breadth First Search (BFS) algorithm. The BFS algorithm is used to find the shortest path for the main character (Pacman) to reach the food objects without encountering the enemies. The goal is to eat two food objects that appear on the screen, and then the game terminates.

2. `main.py`: This file contains the infinite game loop. It initializes the game, handles the movement of the main character using bfs, and continuously updates the game state. The game runs in an infinite loop until there is no path remaining to reach the food. Pacman eats the food, and a new food item generates after that. This process keeps going indefinitely.

## Installation and Running the Game

1. Activate the virtual environment using the following command:
   ```
   source/bin/activate
   ```

2. To run the BFS algorithm, use the following command:
   ```
   python bfs.py
   ```

3. To run the main game loop, use the following command:
   ```
   python main.py
   ```

Note: Make sure to have Python installed on your system before running the game.

![ezgif com-crop](https://github.com/gautam132002/bfs-pacman/assets/68372911/ba0b582d-d49a-4b90-9230-a11b15c7e84f)


## Gameplay

1. The main character (Pacman) starts at a random position in the maze.
2. The enemies and food objects are placed at random positions each time the game starts.
3. Pacman automatically moves towards the food objects using the BFS algorithm to find the shortest path.
4. Pacman must avoid touching the enemies while reaching the food objects.
5. Once Pacman reaches a food object, it is eaten, and a new food item is generated at a random position.
6. In `bfs.py`, the game terminates after Pacman eats two food objects.
7. In `main.py`, the game runs in an infinite loop until there is no path remaining to reach the food. Pacman eats the food, and a new food item generates after that. This process keeps going indefinitely.

Enjoy playing the Pacman game with the Breadth First Search algorithm!
