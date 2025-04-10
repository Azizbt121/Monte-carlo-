# Monte Carlo Simulation for Blackjack

This project implements a basic Monte Carlo simulation for Blackjack. The program simulates multiple rounds of Blackjack games between a player and a dealer (croupier), tracking the results over a number of simulations to provide insights into the outcomes.

## Project Overview

The goal of this project is to simulate a game of Blackjack and analyze the results using a Monte Carlo method. The Monte Carlo simulation runs several iterations of the game, where each round is played according to the standard Blackjack rules, and the outcomes (player win, dealer win, or tie) are recorded. By repeating the game multiple times, we can estimate probabilities of various outcomes in Blackjack.

## Files

- **`monte_carlo_blackjack.py`**: Contains the code for the Blackjack game and the Monte Carlo simulation.
  
## Functions

### `tirer_carte()`
This function simulates drawing a random card from a deck, where the card values range from 2 to 11 (with face cards valued as 10 and Ace as 11).

### `jouer_blackjack()`
This function simulates a single round of Blackjack between the player and the dealer. The player decides whether to hit or stand. The dealer will hit until their total reaches 17. The function returns the result of the game, indicating if the player wins, the dealer wins, or if there is a tie.

### `monte_carlo_blackjack(nombre_simulations)`
This function runs the `jouer_blackjack()` function multiple times (as specified by `nombre_simulations`), recording the number of player wins, dealer wins, and ties. It outputs the results after the simulations are complete.

## Usage.

### Running the Simulation
To run the simulation, change the number of simulations:

nombre_simulations = 1000 

