

# Slot Machine Game

This is a simple command-line slot machine game written in JavaScript. The game allows players to deposit money, place bets on multiple lines, spin the slot machine, and win prizes based on the combination of symbols.

## Prerequisites

Make sure you have the following installed on your machine:

- Node.js (https://nodejs.org)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/slot-machine-game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd slot-machine-game
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Run the game:

   ```bash
   node index.js
   ```

## How to Play

1. Deposit Money:
   - You will be prompted to enter the deposit amount.
   - Enter a positive number to deposit that amount of money.

2. Select Number of Lines to Bet:
   - You will be prompted to enter the number of lines to bet on (1-3).
   - Enter a number between 1 and 3 to choose the number of lines.

3. Place Bet per Line:
   - You will be prompted to enter the bet amount per line.
   - Enter a positive number that is within your balance and bet limits.

4. Spin the Slot Machine:
   - The slot machine will generate random symbols for each reel.
   - The symbols will be displayed on the screen.

5. Check if You Won:
   - The game will determine if you have won based on the combination of symbols on each line.
   - If all symbols on a line are the same, you win a prize based on the symbol's value.

6. Collect Winnings:
   - If you win, the game will add your winnings to your balance.
   - If you lose, your balance will be reduced by the bet amount.

7. Play Again:
   - After each round, you will be prompted to play again.
   - Enter 'Y' to play another round or any other key to exit the game.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

