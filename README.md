All PROJECTS ARE WRITTEN IN SCHEME PROGRAMMING LANGUAGE THAT IS A DIALECT OF LISP.

DESCRIPTION OF PROJECTS:

1. CONVERT ROMAN NUMERALS INTO ARABIC NUMERALS
   Example: Converstion of mcmlxxi into 1971

2. PROJECT: SCORING POKER HANDS
                          
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

3. PROJECT: SPELLING NAMES OF HUGE NUMBERS
  Project description:
  Write a procedure number-name that takes a positive integer argument and returns a sentence containing that number spelled out in words:
  Example (number-name 5513345) result '(five million five hundred thirteen thousand three hundred fourty five)
