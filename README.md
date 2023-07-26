Blackjack card game played on the command line
This game has a 12 step process of playing the actual game which are outlined below, the game uses 4 classes to simulate the gameplay.

Classes:

    Card - contains the value of the player
    Deck - populate a deck via the Card class
    Bank - Contains the data for players "money" that they can bet
    Hand - Holds card objects forthe player and determines whether Ace is a 1 or 11


Gameplay steps:

		1. Create a deck of 52 cards
		2. Shuffle the deck
		3. Ask the Player for their bet
		4. Make sure that the Player's bet does not exceed their available chips
		5. Deal two cards to the Dealer and two cards to the Player
		6. Show only one of the Dealer's cards, the other remains hidden
		7. Show both of the Player's cards
		8. Ask the Player if they wish to Hit, and take another card
            9. If the Player's hand doesn't Bust (go over 21), ask if they'd like to Hit again
		10. If a Player Stands, play the Dealer's hand, the dealer will always Hit until the Dealer's value meets or exceeds 17
		11. Determine the winner and adjust the Player's chips accordingly
            12. Ask the Player if they'd like to play again
