# Card Games in Java

This Java program is a simple implementation of card games, specifically focusing on a simplified version of the card game "Blackjack." The code consists of four classes: `Main`, `Hand`, `Deck`, and `Card`.

## How to Use

1. **Starting the Game**

   Run the `Main` class to start a card game. The program initializes a deck of 52 cards and shuffles them for each new game.

2. **Placing a Bet**

   The game will prompt you to enter your bet amount. Simply input the amount you want to bet, and the game will proceed.

3. **Dealing Cards**

   - The dealer and the player will each receive two cards.
   - One of the dealer's cards will be shown (face-up).
   - Both of the player's cards will be shown.

4. **Playing the Game**

   You will be asked to choose between "HIT" (press 1) or "STAND" (press 0). The objective is to get as close to 21 as possible without going over.

   - "HIT": Receive an additional card.
   - "STAND": Keep your current hand.

   If your hand value exceeds 21, you bust, and the dealer automatically wins. The same applies to the dealer.

5. **Determining the Winner**

   - If you get 21 with your initial two cards (a "Blackjack"), you win 3 times your bet amount.
   - If the dealer busts (goes over 21) and you don't, you win 3 times your bet.
   - If you have a higher hand value than the dealer (without busting), you win 3 times your bet.
   - If both you and the dealer have the same hand value, it's a draw.
   - In all other cases, you lose your bet.

6. **Replaying**

   You can play another round by restarting the program.

## Classes

- **Main**: Contains the game logic, user interface, and flow of the game.
- **Hand**: Represents a player's hand of cards. Handles adding, removing, displaying, and calculating the value of cards in a hand.
- **Deck**: Represents a deck of 52 cards. Handles shuffling, dealing cards, and checking if the deck is empty.
- **Card**: Represents a playing card with a suit, value, and a face-up/down state.

## Example Usage

Here's an example of how you can use this card game:

1. Run the `Main` class.
2. Enter your bet amount.
3. Follow the prompts to play the game, choosing to "HIT" or "STAND" as you see fit.
4. The game will determine the winner based on the rules described above.

Feel free to modify and expand upon this code to create more complex card games or add additional features. Enjoy playing card games in Java!
