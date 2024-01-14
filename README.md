# Rubic Cube Solver

This Python project includes an algorithm to solve the Rubik's Cube.

## About the Project

This project contains an algorithm developed to solve the Rubik's Cube. The algorithm aims to solve the cube by applying different movements on the cube.

## How to Use

1. Clone the project to your computer or download it as a ZIP file.
2. If Python is not installed, download and install Python from the [official Python website](https://www.python.org/downloads/).
3. Open a terminal or command prompt and navigate to the directory where the project is located.
4. Run the `Algo_project_rubic_cube_solver.py` file to start the algorithm:

    ```bash
    python Algo_project_rubic_cube_solver.py
    ```

5. Wait until the cube is solved and observe the solution steps.

## Example Usage

Below is a simple example of using the project to solve a Rubik's Cube:

```python
from Algo_project_rubic_cube_solver import initialize_state, solve_cube

# Create the initial cube state
cube_state = initialize_state()

# Solve the Rubik's Cube
solve_cube(cube_state)
