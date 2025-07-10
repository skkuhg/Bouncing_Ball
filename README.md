
# Bouncing Ball in Spinning Hexagon

## Introduction
This project simulates a bouncing ball inside a rotating hexagon using Pygame. The ball interacts with the edges of the hexagon and bounces off the walls with realistic physics applied, such as gravity, friction, and bounce damping. The hexagon rotates continuously, providing an interesting dynamic visual effect.

## Installation Instructions
To run the code, you will need Python installed on your system. The project requires the following Python libraries:

- **pygame**

You can install the required libraries using pip:

```bash
pip install pygame
```

## Usage Instructions
1. Clone or download this repository.
2. Ensure that Python 3.x is installed along with the required libraries.
3. Run the Jupyter notebook (`Bouncing_Ball.ipynb`) in a Jupyter notebook environment or a Python IDE.

```bash
jupyter notebook Bouncing_Ball.ipynb
```

This will open the notebook in your browser, and you can run the code to see the simulation in action.

## Code Explanation

### Key Components:
- **Pygame Setup**: The code initializes Pygame, sets up screen dimensions, colors, and constants for the simulation.
- **Hexagon Geometry**: A rotating hexagon is drawn, and the vertices are recalculated as it spins.
- **Ball Physics**: The ball is affected by gravity and friction, and it bounces off the hexagon’s edges. Energy loss is simulated during each bounce, and the ball is given an initial velocity.
- **Main Loop**: The main game loop updates the ball’s position, checks for collisions, and handles user input for quitting the simulation.

### Functions:
- **get_hexagon_vertices()**: Calculates the current hexagon vertices based on the rotation angle.
- **get_hexagon_edges()**: Returns the edges of the hexagon, which are used for collision detection.
- **main()**: The main function that handles the game logic, ball physics, and Pygame rendering.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
