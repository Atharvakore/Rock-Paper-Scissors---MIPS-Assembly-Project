
# Rock Paper Scissors - MIPS Assembly Project

## Overview

This project implements a Rock Paper Scissors game in MIPS Assembly, where two computer players compete against each other. The game simulates random moves for both players, compares their choices, and determines the winner of each round. The project also explores the use of Elementary Cellular Automata (ECA) for generating random numbers, replacing traditional random number generation methods.

## Features

- **Random Number Generation**: Utilizes MIPS random number generation syscalls to generate random moves.
- **Game Simulation**: Simulates a single round of Rock Paper Scissors and announces the winner.
- **Elementary Cellular Automaton (ECA)**: Implements ECA to generate pseudorandom numbers, enhancing the randomization process in the game.

## Project Structure

- `random.s`: Contains functions for generating random bits and bytes using MIPS syscalls and ECA.
  - **`gen_bit`**: Generates a random bit.
  - **`gen_byte`**: Generates a random byte by uniformly sampling three results.
- `rps.s`: Contains the function for simulating a round of the Rock Paper Scissors game.
  - **`play_game_once`**: Simulates a single round and announces the result (win, lose, tie).
- `automaton.s`: Implements the ECA and related functions.
  - **`print_tape`**: Prints the current state of the ECA tape.
  - **`simulate_automaton`**: Simulates one generation of the ECA and updates the tape.



## License

This project is part of the Programming 2 course at Saarland University and is subject to the university's academic policies.

