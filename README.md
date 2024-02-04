# Pokemon Battle Simulator

A simple Pokemon battle simulator with Python that allows you to create and manage Pokemon fighters. The Pokemon can be fed, attacked, and have their information displayed.

## Features

- Generate random Pokemon with unique attributes.
- Retrieve Pokemon images and names from the PokeAPI.
- Simulate battles between different types of Pokemon: regular, fighters, and wizards.
- Feed your Pokemon to increase their health points.

## Getting Started
### Prerequisite

- Python 3.x
- requests library
- datetime libary
- random libary

### Installation

1. Clone the repository
```
      git clone https://github.com/your-username/pokemon-battle-simulator.git
      cd pokemon-battle-simulator
```
2. Install the required library
```
   pip install requests
```

### Usage

1. Run the script
```
python pokemon_battle_simulator.py
```
2. Follow the on-screen instructions to create, feed, and battle your Pokemon.

# Code Overview
## Pokemon Class

### Attributes:
- **pokemon_trainer**: _The trainer's name who owns the Pokemon._
- **pokemon_number**: _A random number representing the Pokemon._
- **img**: _URL of the Pokemon image obtained from the PokeAPI._
- **name**: _The name of the Pokemon obtained from the PokeAPI._
- **hp**: _Health points of the Pokemon._
- **power**: _Power points of the Pokemon._
- **last_feed_time**: _Timestamp of the last time the Pokemon was fed._

### Methods
- **get_img()**: _Retrieves the Pokemon image from the PokeAPI._
- **get_name()**: _Retrieves the Pokemon name from the PokeAPI._
- **info()**: _Displays information about the Pokemon._
- **attack(enemy)**: _Initiates a battle with another Pokemon or wizard._
- **feed(feed_interval, hp_increase)**: _Feeds the Pokemon to increase its health points._
