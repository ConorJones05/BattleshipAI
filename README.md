# Battleship Game and AI Strategy

## Overview
This repository contains a Python script that simulates a simplified version of the Battleship game and provides tools to analyze ship placements. Additionally, it lays the groundwork for implementing an AI using OpenAI Gym to perform reinforcement learning analysis, aiming to find the best ship placements and develop optimal strategies for hitting other ships.

## Prerequisites
- Python 3.x
- Required libraries:
  ```bash
  pip install numpy sympy matplotlib datascience
  ```

## Usage
Run the script by executing the following command:
```bash
python battleship_game.py
```
This will generate ship placements, test the fairness of these placements, and display a heatmap of the placements.

## Code Explanation
- **Libraries Used:** `numpy`, `random`, `sympy`, `matplotlib`, `datascience`
- **Game Simulation:** Functions for horizontal and vertical ship placements, ship fairness testing, and distribution analysis.
- **Fairness Testing:** Ship placements are analyzed for fairness using horizontal and vertical distribution testing.
- **Heatmap Generation:** The script generates a heatmap of ship placements on the game board.
- **AI Implementation:** Sets the groundwork for future AI development using OpenAI Gym to find optimal ship placements and hitting strategies.

## Future Work
- Implementing an AI using OpenAI Gym to perform reinforcement learning analysis for the Battleship game.
- Developing and testing various AI strategies for optimal gameplay.

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. All contributions are welcome!
