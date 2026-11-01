# Workout Tracker

A Java command-line application for logging workouts, saving exercise data, and reviewing workout history.

## The Problem

Workout progress is hard to measure when exercise details are scattered across notes, apps, or memory. This project provides a simple local tracker so users can consistently record sets, repetitions, weights, and workout dates, then review that history without depending on a complex fitness platform.

## How It Works

The version 1.0 plan focuses on three core jobs:

- Log exercises with sets, repetitions, weights, and a workout date.
- Store each workout in an ArrayList and save the records to a CSV file.
- Load saved records and display previous workouts from the main menu.

The planned program flow is:

Design source: [System Diagram.drawio](docs/System%20Diagram.drawio)

## Tech Stack

- **Language:** Java
- **Libraries:** Java standard library, including `LocalDate`, file I/O, and `ArrayList`
- **Data storage:** CSV files
- **External tools:** Git, GitHub, and draw.io

## Setup

The project is currently in the planning and repository-setup stage, so there is not yet a runnable Java build. You can clone the repository and review the design documents now:

```bash
git clone https://github.com/Garretttf3/CS193-Final-Project---Workout-Tracker.git
cd CS193-Final-Project---Workout-Tracker
```

## Usage

The command-line interface is planned to guide the user through a menu like this:

```text
Workout Tracker
1. Log workout
2. View workout history
3. Exit

Choose an option: 1
Exercise: Bench Press
Sets: 3
Repetitions: 8
Weight: 135
Date: 2026-11-01
Workout saved.
```

Actual run commands and verified output will be added when the MVP is implemented.

## Roadmap

The following version 2.0 features come directly from the "Schedule" quadrant of the project Eisenhower Matrix:

- [ ] Track strength progress over time
- [ ] Display weekly workout statistics
- [ ] Create and save workout routines
- [ ] Set personal fitness goals

See the full planning document: [Eisenhower Matrix.pdf](docs/Eisenhower%20Matrix.pdf)

## Repository Structure

```text
.
├── README.md
├── src/
├── tests/
└── docs/
    ├── Eisenhower Matrix.pdf
    └── System Diagram.drawio
```

## Author

[Garretttf3](https://github.com/Garretttf3)
