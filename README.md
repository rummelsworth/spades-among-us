# Spades Among Us

Approximating the "Among Us" game experience with a pack of 52 playing cards.

## How to do it

- Remove the 4 aces & shuffle them. Deal one face down to each player. This is the "role card". Each player must look at their role card and then **must** keep it face-down, hidden from the other players, for the entire game until their character is killed or the game ends. Ace of spades is the impostor. The rest are crewmates.
- Take 20 poker chips (or whatever works). 5 white, 5 red, 5 blue, 5 green. Each player gets 4 "voting chips", 1 of each color. Deal the remaining 4 chips out to indicate each player's character color.
- The stack of 48 remaining cards is the deck.
- Start the game. Each round:
  - One player (could stay the same, could rotate around the table) deals each player 2 cards from the deck.
  - Each player places one card face-down in front of them, as their Location Card, and the other face-down in the center of the game area, as an Event Card.
  - When all players have each placed their 2 cards, each player flips their Location Card face-up.
  - The dealer takes the 4 central face-down cards, shuffles them (to disguise who placed which card), and then simultaneously reveals all 4 cards.
  - For each revealed card:
    - If spades, then any player whose Location Card value (2--K) matches the revealed card value is Killed, their Role Card is revealed, and a Meeting is called.
    - If clubs, then if any player's Location Card is clubs or spades, the revealed card is added to the Sabotage pile.
    - If diamonds, then if any player's Location Card is diamonds or hearts, the revealed card is added to the Completed Task pile.
    - If hearts, then if any player's Location Card value matches the revealed card value, an Emergency Meeting is called.
  - If no meeting is called, play proceeds to the next round.
  - When a meeting is called, there's discussion until all players have voted on who they want to eject as the alleged impostor. To vote, a player secretly selects their voting chip with the same color as the player they want to eject, then holds the chip hidden in the palm of their hand, and holds their closed hand out over the center of the table, and keeps it closed until all players have voted (i.e. put their closed hands into the center). To skip vote, a player uses the chip that is their own character's color. When all players have voted, all players open their hands to reveal the chip they selected. The player with the most votes (at least 2) is ejected. If no one has at least 2 votes, no one is ejected and play proceeds to the next round.
  - To proceed to the next round, all cards played in this round (except cards placed in the Sabotage and Completed Tasks pile) are discarded.
  - When the deck is exhausted, the discard pile is taken, shuffled, and used as the new deck.
  - The game is over when:
    - the impostor is Ejected (voted out) or Caught (killed). The crewmates win.
    - two crewmates are eliminated (ejected or killed). The impostor wins.
    - the Completed Tasks pile has 6 or more cards in it than the Sabotage pile. The crewmates win.
    - the Sabotage pile has 7 or more cards in it. The impostor wins.
- The exact numbers for the Tasks/Sabotage win conditions should probably be tweaked or at least verified with more playtesting.
- You can probably play this with 3 players, just setting up and playing it like the 1st crewmate has already been killed.

---

Copyright 2025 William Rummler, George Rummler, Rose Rummler.

https://youtu.be/3mbvWn1EY6g?si=G7DmEsVVHv53iyFw
