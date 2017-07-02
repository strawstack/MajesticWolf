# Pure Functional Games

![](./files/img2.png)

## Overview

This project involves designing and implementing games in Mathematica by examining classical games for inspiration and employing pure functions and combinators. Pure functions will be used to allow players to alter the state of the game in order achieve a specified objective, and combinators will be studied as their properties may be useful to extend the depth and strategy of the games.

Classical card games and board games often involve a combination of random elements and also a way for players to influence their performance by employing strategy. This project will mimic those characteristics and adjust them as necessary to create various games.

An example of a game based on pure functions may operate roughly as follows. The game board is represented by a graph and begins with a single vertex. The vertex represents an argument to a function. Each player holds in their hand a list of functions, which they apply to the verticies of the graph to effect the game. When a function from a player's hand is applied to a vertex the result is placed on the board as a new vertex and an edge is drawn between the two verticies. The goal of the game is to be the last one to make a move such that the next player is unable to find a vertex containing a valid argument to any of the functions they hold in their hand. 

## Games

Three different types of games were created for this project. A functional game where each player applies pure functions to their grid in order to create as many eights as they can before the deck runs out. A interactive visualization where the player must use turing machine style options in order to surf on cellular automata with the goal of collecting blue gems. And lastly, a clone of bomberman where the playing field is rule 30.

### GreatEights

### CellularSurfer

### BomberMan



This project is part of the 2017 Wolfram Summer School.
