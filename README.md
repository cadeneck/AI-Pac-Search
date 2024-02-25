
# Pacman Pathfinding Project

## Introduction
This project involves developing a Pacman agent to efficiently navigate and solve mazes within a game environment. The primary goal is to implement various search algorithms to enable Pacman to find paths to specific locations and collect food efficiently. This README outlines the project structure, installation instructions, and usage guidelines.

### Key Features
- Implementation of general search algorithms (DFS, BFS, UCS, A*).
- Application of these algorithms in various Pacman scenarios.
- Autograder included for self-assessment.

## Installation
To run this project, you'll need Python installed on your machine. Download the project code, then extract the zip archive.

### Dependencies
- Python (version 3.x recommended)
- Pygame (for graphics display, optional)

## Usage
To start a game of Pacman, navigate to the project directory and run:

```bash
python pacman.py
```

To test the search algorithms, you can use the autograder:

```bash
python autograder.py
```

For specific scenarios or to use different search strategies, refer to the commands.txt file or use the `-h` option for help:

```bash
python pacman.py -h
```

## Files and Directories
- `search.py`: Contains all search algorithms.
- `searchAgents.py`: Defines the Pacman agents using search algorithms.
- `pacman.py`: The main file to run Pacman games.
- `game.py`: Logic for the game environment.
- `util.py`: Useful data structures for implementing search algorithms.
- `test_cases/`: Directory containing test cases for autograder.
- Other supporting files for graphics and game mechanics.

## Contributing
While this project was primarily an academic exercise, contributions or suggestions for improvements are welcome. Please open an issue or a pull request if you have suggestions.

## License
This project is licensed under the MIT License - see the https://inst.eecs.berkeley.edu/~cs188/sp22/projects/ file for details.
## Acknowledgments
- Course staff and fellow students for their support and feedback.
- The original creators of Pacman for inspiring this educational project.
