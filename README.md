![Balatro Banner](balatro-banner.png)

# Simulating Balatro

This repository contains the Balatro game simulation created for the ISYE 6644 final project.

## Contents

- `Simulating Balatro - Code.ipynb` — Jupyter notebook with the full simulation, analysis, and visualizations.
- `Simulating Balatro - Monte Carlo Analysis for Better Game Development.pdf` — a written report with model details and findings.

## Running the Simulation

Open `Simulating Balatro - Code.ipynb` in Jupyter Notebook or JupyterLab, then execute the notebook cells from top to bottom.

## Sample Simulation Output

Below is an example snippet of what the simulation output looks like for one run of the Balatro game:

```text
/\/\/\/\/\ Starting Ante 1 /\/\/\/\
Active Jokers: ['None']
Active Planets: ['None']

Ante 1, Blind 1, Target: 300
Play 1: Full House | Chips: 40, Mult: 4, Score: 196 | Running Total: 196 | Cards left in deck: 31 | Redraw: Yes
Play 2: Two Pair | Chips: 20, Mult: 2, Score: 73 | Running Total: 269 | Cards left in deck: 27 | Redraw: Yes
Play 3: Two Pair | Chips: 20, Mult: 2, Score: 78 | Running Total: 347 | Cards left in deck: 16 | Redraw: Yes
Cleared target 300 with cumulative score 347 in 3 plays.

Ante 1, Blind 2, Target: 450
Play 1: Two Pair | Chips: 20, Mult: 2, Score: 87 | Running Total: 87 | Cards left in deck: 38 | Redraw: Yes
Play 2: Flush | Chips: 35, Mult: 4, Score: 181 | Running Total: 268 | Cards left in deck: 33 | Redraw: No
Play 3: Two Pair | Chips: 20, Mult: 2, Score: 76 | Running Total: 344 | Cards left in deck: 28 | Redraw: No
Play 4: Two Pair | Chips: 20, Mult: 2, Score: 76 | Running Total: 420 | Cards left in deck: 23 | Redraw: No
Play 5: Full House | Chips: 40, Mult: 4, Score: 204 | Running Total: 624 | Cards left in deck: 18 | Redraw: No
Cleared target 450 with cumulative score 624 in 5 plays.

New Joker obtained: Devious Joker
New Planet obtained: Mars

Ante 1, Blind 3, Target: 600
Play 1: Two Pair | Chips: 20, Mult: 2, Score: 78 | Running Total: 78 | Cards left in deck: 44 | Redraw: No
Play 2: Straight | Chips: 130, Mult: 4, Score: 571 | Running Total: 649 | Cards left in deck: 33 | Redraw: Yes
Cleared target 600 with cumulative score 649 in 2 plays.

/\/\/\/\/\ Starting Ante 2 /\/\/\/\
Active Jokers: ['Devious Joker', 'Shoot the Moon']
Active Planets: ['Jupiter', 'Mars']
```

## Notes

- Add the attached Balatro banner image to this repository as `balatro-banner.png` so it displays at the top of this README.
- The notebook includes the full game logic, simulation loop, and Monte Carlo analysis.

## Author

- Calvin Choi
