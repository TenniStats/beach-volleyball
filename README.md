# Beach Volleyball Match Data

This repository contains **most** beach volleybal men's and women's match data from the AVP & FIVB tours between 2000 and Aug 2017.

**Some notes:**

The player names have been sorted alphabetically for a winning or losing team. This means that "Nick Lucena" should always appear in "w_player1" and "Phil Dalhauser" should appear in "w_player2".

Age is calculated as: (event date - birthdate) / 365.25, rounded to 7 decimals.

"w_rank" and "l_rank" follow the convention "seed, qualifier". If players have individual seeds (e.g. in King of Beach), only the second players seeding is retained at the time of the data pull, but before the players have been sorted alphabetically. This means that for these matches, the seeding may not correspond to the correct player.

Match stats (columns 34:65) represent match totals. Available for Contender's Bracket and above for about 20 FIVB and most AVP tournaments. "hitpct" represents (kills - errors) / attacks

# License
Attribution required. Non-commercial use only
