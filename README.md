# Optimization of CNC Cutting Points using Evolutionary Computation

## Description

This project aims to optimize the layout of parts on metal sheets for CNC machines, reducing material waste, energy consumption, and machine time. Currently, a **Genetic Algorithm (GA)** is implemented to solve the problem.

## Project Structure

- **app.py:**  
  The main file that instantiates and runs the Genetic Algorithm.
- **genetic_algorithm.py:**  
  Contains the implementation of the Genetic Algorithm, including methods for population initialization, layout decoding, evaluation, selection, crossover, mutation, and the main evolutionary loop.
- **ant_colony.py, differential_evolution.py, particle_swarm.py:**  
  Other evolutionary algorithm implementations (Ant Colony, Differential Evolution, and Particle Swarm) are included in the project but **are not currently called** in `app.py`.

## How to Run

1. Clone the repository.
2. Navigate to the project folder.
3. Run the `app.py` file:
   ```bash
   python app.py
