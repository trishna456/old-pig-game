# Pig Game

A simple dice game for two players, built with HTML, CSS, and JavaScript.

## Game Rules

1. The game has 2 players, playing in rounds.
2. In each turn, a player rolls a dice as many times as they wish. Each result is added to their ROUND score.
3. BUT, if the player rolls a 1, all their ROUND score gets lost. After that, it's the next player's turn.
4. The player can choose to 'Hold', which means that their ROUND score gets added to their GLOBAL score. After that, it's the next player's turn.
5. The first player to reach 100 points on the GLOBAL score wins the game.

## Getting Started

### Prerequisites

To run the game, you need a web browser. No additional software is required.

### Installation

To run this project locally, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/trishna456/old-pig-game.git
```

2. Navigate to the project directory:

```bash
cd old-pig-game
```

## Running the Game

1. Open the `index.html` file in your preferred web browser.
2. Enjoy the game!

## Game Controls

- **New Game**: Starts a new game.
- **Roll Dice**: Rolls the dice and adds the result to the current score unless a 1 is rolled.
- **Hold**: Adds the current score to the global score and switches to the next player.

## Code Overview

### JavaScript (`script.js`)

- **Initialization**: The `init` function sets up the game, resetting scores and states.
- **Switch Player**: The `switchPlayer` function handles switching turns between players.
- **Roll Dice**: Event listener on `btnRoll` to handle dice rolls and score updates.
- **Hold**: Event listener on `btnHold` to handle holding the current score and updating the global score.

### CSS (`style.css`)

- Basic styles for layout and design, including player sections, dice image, and buttons.
- Responsive design and visual effects to enhance the gaming experience.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Acknowledgements

- Inspired by various implementations of the Pig Game.
- Dice images and other assets are open source.


