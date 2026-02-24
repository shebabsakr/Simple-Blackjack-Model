A simple browser-based Blackjack game built with HTML, CSS, and JavaScript.
Play a basic round of Blackjack where you try to get as close to 21 as possible without going over.
📌 Overview
This project simulates a simplified version of Blackjack.
Players are dealt two cards initially and can choose to draw additional cards to try to reach 21.
The game shows the cards, current sum, and messages indicating the game state.
🚀 Features
Start a new game with two initial cards
Draw new cards to try reaching 21
Dynamic messages based on the sum:
"Do you want to draw a new card?"
"You've got Blackjack!"
"You're out of the game!"
Displays current cards and sum
Simple and colorful UI
🛠 Technologies Used
HTML5 – Structure
CSS3 – Styling
JavaScript (Vanilla) – Game logic and DOM updates
⚙️ How It Works
On Start Game, two cards are drawn and displayed.
The sum of cards is calculated and shown.
Messages update based on the sum:
Less than 21 → option to draw a new card
Exactly 21 → Blackjack!
More than 21 → game over
Clicking New Card adds a fixed card (or random card if extended) and updates the sum.
