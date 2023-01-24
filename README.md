# rock_paper_scissors
A simulation of the Rock, Paper, Scissors game

Rock-Paper-Scissors is a simple two-player game, where you and your opponent (the computer) simultaneously choose one of the following three options: "rock", "paper", or "scissors". The rules are as follows:
	Rock beats scissors (the scissors get broken by the rock)
	Scissors beats paper (the paper gets cut by the scissors)
	Paper beats rock (the paper covers the rock)
The winner is the player whose choice beats the choice of his opponent. If both players choose the same option (e.g., "paper"), the game outcome is "draw".

The solution is as follows:
Once the game is started 3 variables are defined, representing the three possible options for a player more. Afterwards, the player (person) is prompted by a text("Choose [r]ock, [p]aper or [s]cissors:") to enter into the console one of the three valid options. If the player enters a valid input, then by an if statement it is determined what the player's move is. If the input is invalid, then the game ends and the player gets a "Invalid Input. Try again..." message.

Afterwards, by using the imported random.randint method a number is chosen by the computer. That number can be either 1, 2 or 3, each representing the three possible player options. Again, using an if statement, the program will choose the computer move based on the generated number. Once done, the game will print the computer move: "The computer chose {computer_move}.".

When both the player move and the computer move are chosen, they are compared by using an if statement and a winner is chosen. If the player wins, "You win!" is printed, if the computer wins, "You lose!" is printed and if it is a draw, "Draw!" is printed.

After the winner is chosen, "Type [yes] to Play Again or [no] to quit: " will be printed on the console, prompting the player to choose if he wants to play more. If he types "yes", the program will repeat itself, since everything is in a while loop. If "no" is chosen, "Thank you for playing!" is printed on the console and the game ends. If an invalid answer is typed, "Invalid Input. Try again..." and the game ends.

The game can be tested on the following link:
https://replit.com/@KingTheSim/rockpaperscissors#rock_paper_scissors.py
