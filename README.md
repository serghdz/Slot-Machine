# Slot-Machine
Slot machine program 

This is my first program written in python following a tutorial by [@Tech with Tim](https://www.youtube.com/c/TechWithTim) on youtube. The program simulates a slot machine and has helped me understand fundamental concepts like functions, loops, and nested loops. Additionally, it provided insight into maintaining a structured programming layout.

## Code Overview

The slot machine program uses Python and consists of the following components:

- `main`: The main function that initializes the game loop.
- `deposit`: Function to collect the initial deposit from the user.
- `spin`: Function to handle the spinning of the slot machine.
- `get_number_of_lines`, `get_bet`: Functions to gather user input for lines and bet amounts.
- `get_slot_machine_spin`: Function to generate random slot machine results.
- `print_slot_machine`: Function to display the slot machine results.
- `check_winnings`: Function to check for winning combinations.

## Usage

1. Run the program.
2. Deposit an initial amount.
3. Press enter to play or 'q' to quit.
4. Specify the number of lines and bet amount.
5. View the slot machine results and check for winnings.

## Constants

- `MAX_LINES`: Maximum number of lines to bet on.
- `MAX_BET`: Maximum bet amount.
- `MIN_BET`: Minimum bet amount.
- `ROWS`, `COLS`: Number of rows and columns in the slot machine.

## Symbol Data

The slot machine uses symbols represented by the letters A, B, C, and D. The count and value of each symbol are defined in `symbol_count` and `symbol_value` dictionaries.

Feel free to explore and modify the code to enhance your understanding of Python programming!
