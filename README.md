# Beggar-My-Neighbour: the search for the longest finite game

**Results page: https://jorist78.github.io/beggar-my-neighbour-results/**

Beggar-My-Neighbour is a card game without any decisions: once the cards are dealt, the whole game
is fixed. Some deals end after a few dozen cards, a very few last for thousands. Since a deal that
never ends has been found, the open question is how long a game can be and still finish.

This repository hosts the results page of a GPU search for such long games. It has evaluated
hundreds of trillions of deals so far. The page shows

- our longest game so far, with its deal, cards and tricks, and where it ranks among the known games,
- the history of our best games,
- how many games have been evaluated, including a 24-hour turbo run on rented GPUs.

The page is regenerated automatically: right after a new best game, and about once a day while the
search runs. The longest known games, found by many people over the years, are listed in
[Richard P. Mann's register of records](https://richardpmann.com/beggar-my-neighbour-records.html).
