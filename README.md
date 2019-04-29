# Catch The Pink Flamingo

### Context
All the data are about a mobile game, named “Catch the Pink Flamingo”. It’s produced by Eglence Inc. 
It’s a multi-user game where the players have to catch Pink Flamingos that randomly pop up on a gridded world map based on missions that change in real-time.

### Objective
The objective of the game is to catch as many Pink Flamingos as possible by following the missions provided by real-time prompts in the game and cover
 the map provided for each level. The levels get more complicated in mission speed and map complexity as the users move from level to level.

### Problem Statement
The “catchThePinkFlamingo” contains a single CSV file created by aggregating data from several game data files.
It is intended to be used for identifying big spenders

### Solution
I used “catchThePinkFlamingo.csv”, and classified users with Decision Tree in Python to identify big spenders in the game.
The objective is to predict which user is likely to purchase big-ticket items while playing game. 
Using the file “catchThePinkFlamingo.csv”, I defined two categories for price: HighRollers, who spend more than $5.00 to buy the items, and PennyPinchers, who spend $5.00 or less to buy the items. 
In this graph, red stands for the PennyPinchers, blue stands for the HighRollers.

### Specific Recommendations to Increase Revenue
	- Offer more products to iPhone users.
	- Offer some promotions to PennyPinchers for attracting their consommation.

