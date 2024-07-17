# Slot Machine Game

This is a simple slot machine game implemented in Python. The player can deposit money, place bets on multiple lines, and spin the slot machine to win or lose money based on the outcome.

## Features

- Deposit money to start playing
- Bet on up to 3 lines
- Spin the slot machine to see if you win
- Different symbols with different values
- Check winnings and display winning lines

## Rules

1. You can bet on 1 to 3 lines.
2. The bet amount must be between $1 and $100.
3. The total bet is the bet amount multiplied by the number of lines.
4. If you win, your winnings are calculated based on the symbol values and your bet amount.

## Symbol Values

- **A**: 5
- **B**: 4
- **C**: 3
- **D**: 2

## Getting Started

### Prerequisites

- Python 3.x

### Running the Game

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/slot_machine.git
    ```

2. Navigate to the project directory:

    ```bash
    cd slot_machine
    ```

3. Run the game:

    ```bash
    python slot_machine.py
    ```

## How to Play

1. Deposit money to start.
2. Enter the number of lines to bet on.
3. Enter the bet amount for each line.
4. Spin the slot machine and see if you win!
5. The game will continue until you decide to quit by pressing `q`.

## Example

What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 3
What would you like to bet on each line? $10
You are betting $10 on 3 lines. Total bet is equal to: $30
C | B | A
D | C | B
D | A | C
YOU WON $0!
You won on
Current Balance is $70
Press enter to play (q to quit).

## Acknowledgments

- Thanks to the Tech With Tim for providing guidance
