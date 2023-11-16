# Gambling-Game
The provided Python code implements a simple console-based dice game for 2 to 4 players. Here's a detailed description:

Player Initialization:

Users are prompted to input the number of players, and the input is validated to ensure it falls within the range of 2 to 4 players.
Game Loop:

The game runs in a loop until one of the players reaches or exceeds a maximum score of 50.
Player Turns:

For each player's turn, the program prints the player number and their current total score.
Players are asked if they want to roll the six-sided die (y to roll, any other input to skip the turn).
If a player chooses to roll, a random value is generated using the roll function.
If the value is 1, the player's current turn score is reset to 0, signaling the end of their turn.
Otherwise, the value is added to the current turn score, and the player can choose to roll again.
The player's total score is updated after each turn.
Determining the Winner:

Once a player's total score reaches or exceeds the maximum score of 50, the game ends.
The player with the highest total score is declared the winner.
If there is a tie (multiple players have the same highest score), the first player with that score is declared the winner.
Output:

The program provides informative output, including player numbers, current scores, rolled values, and the final winner.
Functions:

The code defines a roll function, which generates a random value between 1 and 6, simulating a six-sided die roll.
User Interaction:

The code incorporates user-friendly prompts, guiding players through each turn and allowing them to decide whether to roll the die.
Code Structure:

The code is structured with loops and conditionals to handle player turns, score tracking, and determining the winner.
In summary, this Python code creates a turn-based dice game where players compete to be the first to reach or exceed a total score of 50. The game involves rolling a die, accumulating points, and declaring a winner based on the highest total score.
