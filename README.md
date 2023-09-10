# PlanetaryTopTrumps
A variant of the game of Top Trumps using 9 cards, one for each of planet of our Solar System


Here, the cards and data about the planets are stored in a list of lists, equivalent to a two-dimensional array, called planets. The “array” will contain 9 rows (from 0 to 8) and 5 columns (0 to 4) with the following columns/fields:
- Name of the planet,
- Distance from the Sun (in million km),
- Size (Diameter) in km,
- Orbital Period in days,
-  Number of Moons.

GAME RULES:
Randomly picks a planet/card from the deck and display all its data on screen,
Randomly picks a planet for the computer, without displaying it on the screen,
Asks the end-user which criteria to compare for this round: (1-Distance from the Sun, 2-Size, 3-Orbital Period,4-Number of Moons),
Compares both cards using the chosen criteria,
Tells the player whether they won, drew or lost,
Gives the computer or the player points: 3pts for a win, 1pt for a draw,
Displays both the computer and the player’s scores and repeats the whole process until the player or the computer reaches a score of 12 and hence win the game.
