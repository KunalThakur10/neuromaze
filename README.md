# NeuroMaze

**NeuroMaze** is a Python-based AI simulation where autonomous agents evolve over generations to solve procedurally generated mazes. Built entirely in raw Python with no external libraries, the project demonstrates a simplified genetic algorithm and pathfinding logic in a purely textual interface.

## Features

- Procedural maze generation with customizable dimensions
- Evolutionary algorithm using selection, crossover, and mutation
- Agents learn optimal paths over time based on fitness evaluation
- Fully terminal-based output with ASCII maze visualization
- No dependencies or external libraries required

## How It Works

1. A random maze is generated with walls and a defined start and end point.
2. A population of agents is created, each with a random sequence of movement instructions.
3. Agents are evaluated based on how close they get to the goal and whether they reach it.
4. The top-performing agents are selected to reproduce through crossover and mutation.
5. This process repeats for a set number of generations, improving the population’s ability to solve the maze.

## Usage

### Requirements

- Python 3.x
- No external libraries required

### Running the Simulation

```bash
python neuromaze.py
