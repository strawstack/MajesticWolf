# Pure Functional Games

This project involves designing and implementing a variation on a classically inspired game using pure functions and combinators. Pure functions will be used to allow players to alter the state of the game in some way in order achieve a specified objective, and combinators will be studied as their properties will be useful to extend the depth and strategy of the game.

Classical games like card games, board games, and tic-tac-toe often involve a combination of random elements and also a way for players to influence their performance by employing strategy. This project will mimic those characteristics and adjust them as necessary to create a robust, accessible, and deep game.

An example of a game based on pure functions may operate roughly as follows. Each players is dealt a number of pure functions. Several list manipulating functions are 'revealed' from a shared deck. The game board is represented by an n by n matrix of non-prime integers. During a player's turn, they take one or more functions from the shared deck and apply them to the pure functions in their hand in order to effect the game board. The goal is to make as many prime numbers appear on the game board as possible for which the player receives points. The game ends when both players run out of pure functions or pass their turns.

This project is part of the 2017 Wolfram Summer School.
