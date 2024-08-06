# Blackjack-Game
This is a simple text-based Blackjack game implemented in Python. The game allows a player to play against the dealer, simulating a typical Blackjack experience. The player can choose to "hit" or "stay" and the game follows the standard rules of Blackjack.

How to Play
Starting the Game: The game starts by dealing two cards each to the player and the dealer.
Player's Turn: The player can choose to either "hit" (take another card) or "stay" (keep their current hand).
Dealer's Turn: The dealer reveals their cards and hits until their total is 17 or more.
Winning Conditions:
If the player's total exceeds 21, the player busts and loses.
If the dealer's total exceeds 21, the dealer busts and the player wins.
If the player's total is 21, the player wins with a Blackjack.
If the dealer's total is 21, the dealer wins with a Blackjack.
The player wins if their total is higher than the dealer's without exceeding 21.
The dealer wins if their total is higher than the player's without exceeding 21.
If both totals are the same, the game is a tie.
Code Overview
Functions
showCard(d): Displays the cards in a given hand.
addCards(s, card): Calculates the total value of a hand, handling special cases for face cards and aces.
Game Loop
The game loop continues until the player chooses to stop.
The initial cards are dealt to both the player and the dealer.
The player's cards are displayed and the player is given the choice to "hit" or "stay".
If the player chooses to "hit", they receive another card and their new total is calculated.
If the player chooses to "stay", the dealer reveals their cards and hits until their total is 17 or more.
The game determines the winner based on the totals of the player's and dealer's hands.
The game can be continued or stopped based on the player's choice.
