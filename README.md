# AI-AGENT-GO-GAME-Strategic-Game-Analyzer
# GameState Manager

**GameState Manager** is a Python-based project designed to manage and analyze game states for a strategic game. It allows you to load game states from an input file, identify player sides, check for KO situations, and update the game board accordingly.

## Features

- **Read Game State**: Load the current and previous game states, along with the player's side (black or white).
- **Check KO Situation**: Verify if a move results in a "KO" where the board returns to a previous configuration.
- **Group Removal**: Remove a group of stones for a specific player based on their connected stones.
- **Player Side Detection**: Easily determine the current and opponent's sides.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- NumPy

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/GameStateManager.git
   cd GameStateManager

