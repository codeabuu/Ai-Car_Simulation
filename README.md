# Autonomous Car Simulation with NEAT

This project demonstrates an autonomous car simulation using the NEAT algorithm. The simulation uses `pygame` for graphical rendering and `neat-python` to evolve neural networks that control the car's movement. The goal is to train the car to navigate a track without crashing into the borders.

## Features

- Autonomous car controlled by evolved neural networks.
- Real-time simulation using `pygame`.
- Configurable NEAT parameters for custom experiments.
- Visualization of the car's sensors and movement.

## Installation

### Prerequisites

- Python 3.x
- `pip`

### Steps

1. Clone the repository.
   ```bash
   https://github.com/codeabuu/Ai-Car_Simulation.git
   ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
   
## Usage

1. Ensure you have the following files in your working directory:
    - `config.txt` (NEAT configuration file)
    - `car.png` (car sprite image)
    - `map.png` (track map image)

2. Run the simulation:

    ```bash
    python main.py
    ```

3. The simulation window will open, displaying the car's movement and evolution process.

The NEAT configuration is specified in `config.txt`. You can modify this file to experiment with different NEAT parameters.