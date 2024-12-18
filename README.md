# Tuple Out Dice Gamr

## Overview
The Tuple Out Dice Game is a turn-based dice game where players compete to score the most points bt rolling dice strategically. Players must avoid "tupling out" (rolling three of the same number) while deciding whether to re-roll certain dice to improve their score. The game ends when a player reaches the target score (default: 50 points).

## Features
- Turn-based gameplay for multiple players.
- Dice are "fixed" when two show the same value and cannot be re-rolled. 
- Players re-roll any non-fixed dice to improve their score.
- Rolling three of the same number ("tupling out") ends the turn with zero points.
- Real-time visualization of scores using Matplotlib.
- Timing analysis of each player's turn using the `time` module.
- Player turn statistics saved to a CSV file using Pandas.

## Prerequisites
- Python 3.7 or higher must be installed.
- Required libraries:
```bash
pip install matplotlib pandas

This project is licensed under the MIT License. See the LICENSE file for details.
