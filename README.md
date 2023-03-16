# Game-of-War

This is a simple web-based card game called "Game of War" built using HTML, CSS, JavaScript, and the Deck of Cards API. The game is based on the classic children's card game "War", where two players each get half of a shuffled deck of cards and take turns drawing the top card from their own pile. The player with the higher card wins the round and takes both cards. The game continues until one player has all 52 cards, at which point they are declared the winner.

In this web version, the user plays against the computer and can interact with the game through two buttons: "New Deck" and "Draw Card". Clicking "New Deck" fetches a new shuffled deck of cards from the Deck of Cards API and resets the game to the starting state. Clicking "Draw Card" draws a card from both the user's and the computer's pile, compares them, and displays the result (win, lose, or tie) as well as the updated number of cards in each pile. When one player has all 52 cards, a message declaring the winner is shown.

The project uses modern web development tools and techniques, including responsive design, asynchronous programming with Promises, and modular code organization. The Deck of Cards API provides a convenient and reliable source of randomized playing cards and eliminates the need for the game to implement its own shuffling and dealing logic.


# Technologies-Used

HTML

CSS

JavaScript

Deck of Cards API

#Features

Responsive design

Asynchronous programming with Promises

Modular code organization

Shuffling and dealing logic provided by Deck of Cards API

Simple game mechanics based on classic card game

#How-to-Play

Click "New Deck" to fetch a shuffled deck of cards from the Deck of Cards API and start a new game.

Click "Draw Card" to draw a card from both the user's and the computer's pile.

Compare the two cards to determine the winner of the round.

If the user wins, they take both cards and add them to their pile. If the computer wins, the opposite happens. In case of a tie, both cards remain on the table and 
another round is played.

Repeat steps 2-4 until one player has all 52 cards, at which point they are declared the winner.
