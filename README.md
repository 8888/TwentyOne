# TwentyOne
An in-broswer blackjack game!<br>
https://betterin30days.github.io/TwentyOne/<br>
<img src="https://github.com/betterin30days/TwentyOne/blob/master/screenshots/21.gif"><br>

# Features
-Play is against the dealer, following standard casino rules<br>
-By default, single deck blackjack is played. This can be changed with a parameter during setup<br>
-Hit, Stand, Double, and split are available<br>
-A betting system tracks winnings and allows adjustment of bets between each hand<br>
-Standard payouts of 1:1 for winning a hand and 3:2 for blackjack are used<br>

# Design
The display is written using an HTML 5 canvas and the game logic is handled by javascript. The game is object based, using Player objects, Hand objects, and individual Card objects. These objects are passed between each other depending on current ownership. There is a Game object that acts as an interface between all other objects and to handle the game state.

# Screenshots
<img src="https://github.com/betterin30days/TwentyOne/blob/master/screenshots/placebets.JPG"><br>
<img src="https://github.com/betterin30days/TwentyOne/blob/master/screenshots/hand.JPG"><br>
<img src="https://github.com/betterin30days/TwentyOne/blob/master/screenshots/blackjack.JPG"><br>
<img src="https://github.com/betterin30days/TwentyOne/blob/master/screenshots/split.JPG"><br>

*Artwork disclaimer*
I did not make any of the artwork used for the felt background, card faces, and card back. I do not claim ownership of the artwork in this project.
