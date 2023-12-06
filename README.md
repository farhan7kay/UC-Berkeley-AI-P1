# uc-Berkeley-AI-P1

# Pacman AI Projects - Search Algorithms and Heuristics

Welcome to the Pacman AI Projects repository! This project is an interactive and educational exploration of artificial intelligence concepts through the lens of the classic arcade game, Pacman. In this repository, you'll find a hands-on experience of implementing various search algorithms and heuristic functions to control the behavior of the Pacman agent within a maze-like environment. By completing this project, you'll gain a deeper understanding of AI techniques, algorithmic problem-solving, and the practical application of intelligent agents.

## Introduction
The Pacman AI Projects provide you with a dynamic and engaging platform to learn about AI algorithms in a fun and interactive manner. The project focuses on teaching you the core principles of search algorithms and heuristic design. You'll have the opportunity to experiment with different approaches, analyze their behaviors, and witness firsthand how an AI agent, in this case, Pacman, makes decisions and navigates through complex environments.


## Project Structure
The project's structure is designed to help you progressively learn and implement AI concepts. Here are the key components:

- `searchAgents.py`: This module contains classes that define different Pacman agents utilizing various search algorithms and heuristic functions.
- `search.py`: Here, you'll find the implementation of core search algorithms, including Depth-First Search (DFS), Breadth-First Search (BFS), Uniform-Cost Search (UCS), and A* Search.
- `game.py`: This module defines the game environment and interactions between Pacman and the maze.

## Implemented Algorithms
The Pacman AI Projects feature a collection of implemented search algorithms:

- Depth-First Search (DFS): Explore the depth of the search tree before backtracking.
- Breadth-First Search (BFS): Explore all neighboring nodes before moving on to the next level.
- Uniform-Cost Search (UCS): Prioritize paths with the lowest accumulated cost.
- A* Search: Combine cost and heuristic to find the optimal path.

## Heuristic Functions
Incorporate heuristic functions to enhance Pacman's decision-making process. The project includes the following heuristic functions:

- Manhattan Distance Heuristic: Estimate the remaining distance to the goal using Manhattan distance.
- Euclidean Distance Heuristic: Estimate the remaining distance to the goal using Euclidean distance.

## Scenarios and Objectives
Throughout the project, you'll encounter different scenarios that challenge you to apply the implemented algorithms:

1. Finding Paths to Goals: Guide Pacman to discover the shortest path to a specific goal.
2. Reaching Corners: Design a strategy for Pacman to visit all four corners of the maze optimally.
3. Collecting Food: Develop a plan for Pacman to navigate the maze and collect all food pellets using various search strategies.

## Running the Pacman Game
Engage with the Pacman game using a variety of settings:

```bash
python pacman.py -l <layout> -p <agent> -a <algorithm> -z <heuristic>
```

- `<layout>`: Choose a maze layout, such as `mediumMaze` or `openMaze`.
- `<agent>`: Select a Pacman agent class, like `SearchAgent`.
- `<algorithm>`: Specify a search algorithm like `dfs`, `bfs`, `ucs`, or `astar`.
- `<heuristic>`: Utilize a heuristic for A* search, such as `manhattanHeuristic` or `euclideanHeuristic`.

## Evaluation and Testing
Ensure your implementations are correct with the help of included test scripts and autograders.

## Learning Objectives
By participating in the Pacman AI Projects, you will:

- Develop a strong grasp of various search algorithms and their nuances.
- Acquire the skill to design and implement heuristic functions that guide intelligent agents.
- Cultivate proficiency in Python programming, data structures, and algorithmic problem-solving.
- Gain practical experience in debugging, testing, and optimizing AI algorithms.
- Confront the challenges of creating intelligent agents applicable to real-world scenarios.

## Contributing
Contributions to this project are encouraged! If you encounter issues or wish to enhance the project, submit a pull request.
