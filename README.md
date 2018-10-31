Projects are written in SCHEME programming language that is a dialect of LISP.

DESCRIPTION OF PROJECTS:

1. CONVERT ARABIC NUMERALS INTO ROMAN NUMERALS (SCHEME)
 Example: (arabic 'mcmlxxi) result 1971

2. PROJECT: SCORING POKER HANDS (programming language SCHEME/dialect of LISP)
                          
There are different variations of cards and hands in POKER game. The poker player has 5 cards in his hands. 
The idea of this project is to invent a procedure poker-value that 
will tell the player what kind of poker hands the poker player has among his cards.

Here are the various kinds of poker hands, in decreasing order of value:

- Royal-flush: ten, jack, queen, king, and ace, all of the same suit
- Straight flush: five cards of sequential rank, all of the same suit
- Four of a kind: four cards of the same rank
- Full house: three cards of the same rank, and two of a second rank
- Flush: five cards of the same suit, not sequential rank
- Straight: five cards of sequential rank, not all of the same suit
- Three of a kind: three cards of the same rank, no other matches
- Two pair: two pairs of cards, of two different ranks
- Pair: two cards of the same rank, no other matches
- Nothing: none of the above

 Example (poker-value '(s2 d3 s4 d2 h2)) result THREE OF TWOS
 Example (poker-value '(s2 s3 s4 s6 s5)) result STRAIGHT FLUSH - SPADES
 Example (poker-value '(sa sq sj sk s10)) result ROYAL FLUSH - SPADES
 Example (poker-value '(sa h10 d2 sq ck)) result NONE OF THE ABOVE
