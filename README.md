# Evolutionary Neural Maze Race

A browser-based evolutionary experiment where two neural networks race through the same deterministic curriculum of 100 increasingly difficult mazes.

## Rules

- NN1 and NN2 receive the same deterministic set of 100 mazes.
- Each network advances immediately when it solves its current maze.
- The networks do **not** wait for one another.
- There is no maze timeout.
- The first network to solve all 100 mazes wins the generation.
- The winner survives as the next parent.
- A mutated offspring is created to challenge the survivor.
- The process repeats generation after generation.

## Run

Open `index.html` in a modern browser.

MAX CPU mode is enabled by default and uses as much of the browser's available frame-time budget as practical for simulation.

## Controls

- **MAX CPU** — adaptive maximum simulation speed.
- **Pause** — pauses evolution.
- **Restart** — restarts from the genesis networks.
- **Manual speed** — available when MAX CPU is disabled.
- **Mutation** — controls offspring mutation strength.
