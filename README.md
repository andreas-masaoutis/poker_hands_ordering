# poker_hands_ordering
A computational solution to the problem of evaluating poker-variant hands ranking

## The definition of the problem

In poker, there is the ranking of hands, according to the probability of a hand appearing in a round.

https://en.wikipedia.org/wiki/Poker_probability

One complication is that since in some popular variations of poker such as Texas hold 'em, a player uses the best five-card poker hand out of seven cards, the ranking slighly changes.

In Greece, the similar game is called poka and is most probably related to the French version. It is usually played with 32 cards (7 to King, plus Ace), and has many variations with respect the common cards on the table and they ways they are being layed out, the cards the players get, etc. Of course this is reflected on the rankings as well.

The general ranking in poka is the following:

- straight flush
- four of a kind
- flush
- full house
- straight
- three of a kind
- two pairs
- one pair

The rule sais that when the player can choose from 8 (inclusive) or more cards, or when there is a joker card, then `three of a kind` beats `straight` and `full house` beats `flush`. So the ranking becomes:

- straight flush
- four of a kind
- full house
- flush
- three of a kind
- straight
- two pairs
- one pair

The purpose here is to numerically simulate two games, one of each kind, and verify that these indeed follow the supposed rankings.
