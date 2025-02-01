# NEAT-Flappy-Bird

Watch a genetic/evolutionary algorithm (NEAT) slowly progress and teach itself to play Flappy Bird! This project uses the **NEAT-Python** module to evolve a population of neural networks that learn how to navigate the pipes.

![NEAT Flappy Bird Demo](./path/to/screenshot.png)

---

## Overview

- **NEAT Algorithm**: NeuroEvolution of Augmenting Topologies (NEAT) is a method for evolving neural networks that can mutate both their weights and their structure.
- **Flappy Bird Gameplay**: The AI observes the bird’s position and the pipe positions, then decides when to jump in order to pass through the gaps.

In this project, you can watch as the AI’s performance improves over generations. Each generation spawns multiple birds (each with a slightly different neural network), and the best performers get to pass on their “genes” to the next generation.

---

## Requirements

- **Python 3.x**  
- **[NEAT-Python](https://neat-python.readthedocs.io/en/latest/)**  
- **pygame** (to render the Flappy Bird game visually)

You may also need other standard libraries like `random`, `os`, and `sys` depending on your script. Usually, these come pre-installed with Python.

---

## Installation

1. **Clone or Download** this repository:
   ```bash
   git clone https://github.com/utkarshgogna1/Flappy-Bird.git
   cd NEAT-Flappy-Bird
