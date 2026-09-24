# Evolutionary Algorithm N-Queens Solver

This project implements an Evolutionary Algorithm (EA) to solve the classic N-Queens problem. It includes modular algorithm components, visualization utilities, and scripts for running simulations and analyzing results.

## Features

### Core Evolutionary Algorithm
- Population initialization
- Fitness evaluation
- Selection strategies
- Mutation and recombination mechanisms
- Execution loop with configurable parameters
- Multiple algorithm variants (basic and extended implementations)

### N-Queens Problem
- Board representation and state transitions
- Fitness function based on number of conflicts
- Utilities for tracking and displaying board states

### Visualization and Analysis
- Plotting tools for algorithm performance over generations
- Sample output images and data included in the Results directory

### Project Structure

Evolutionary_Algorithm-main/
- Main/
  - board_state.py
  - evolutionary_algorithm.py
  - fitness.py
  - selection.py
  - nqueens.py
  - simple_implementation.py
  - documentation.md
- Results/
  - Evolutionary_Algorithm.txt
  - PlotBackTracking.txt
  - Result1.png
  - result1_parameters.txt
- chatgpt.py
- plot.py
- simple_implementation.py
- run_simulations.bat
- README.md (original)

## Getting Started

### Prerequisites
- Python 3.10+
- Required libraries: matplotlib, numpy

### Running the Evolutionary Algorithm
Run a simulation using:
python simple_implementation.py

Or use the Windows script:
run_simulations.bat

### Plotting Results
python plot.py

## Configuration

You can adjust algorithm parameters inside the implementation scripts, such as:
- Population size
- Mutation rate
- Selection strategy
- Maximum generations
- Board size (N)

Configurations can be modified in:
- Main/evolutionary_algorithm.py
- simple_implementation.py
- Parameter files in the Results folder

## Results

The Results directory contains:
- Output logs
- Parameter sets
- Performance plots
- Example solved board visualizations

## Documentation

Additional explanation and notes can be found in:
Main/documentation.md

## Contributing

You may open issues or submit pull requests to improve the algorithm, add strategies, or enhance visualization tools.

## License

This project is open-source. You may modify and use it freely
