# blackjack-twentyone
A blackjack/21 game made with Python.

## Blackjack Rules:

Blackjack is (apparently) by far the most popular casino game in the United States and across Europe. This is not only because it’s so much fun, but because it has the lowest house edge of any casino game in the world.


### Major Rules of Blackjack
In black Jack, the dealer is your opponent. Whoever scores the most points without exceeding 21, simply wins.


Number cards are worth their value in points, while face cards (jack, queen and king) are worth 10 points. Aces are special: they can be worth either 1 or 11 points. In the current development, they are worth 11.


Each round begins with the player placing their bet. Once this has occurred, the player and the dealer are each dealt two cards. One of the dealer’s cards is exposed, while the other is dealt face-down.


Being dealt 21 with your first two cards is known as a blackjack. Being dealt a blackjack automatically wins the player the hand unless the dealer’s hand is also a blackjack, and vice versa. Both the player and dealer being dealt a blackjack results in a push (that is, all bets being returned).


### Player options
If the player’s starting two cards are worth less than 21 points, they have a number of options:

Hit: the player draws another card. The player can keep on hitting until they reach 21 points or go bust.

Stand: the player sticks with their starting two cards.

Split: the player splits their starting two cards into two individual hands. This is only allowed if the starting two cards are worth the same number of points. Each new hand will be dealt a second card, and play proceeds as normal.

Double: the player doubles their bet, receives one more card, then stands.

Surrender: the player forfeits their hand and is returned half of their initial bet.

After the player has played their hand, the dealer exposes their face-down card. If their hand is worth 17 or more points, they stand. If it’s worth less, they draw another card. The dealer’s and the player’s hands are then compared, and whoever has the best hand wins.


### Rule Variations
There can be slight variations to the rules of blackjack depending on where you play. For example, most casinos will offer an insurance bet to the player if the dealer’s exposed card is an ace, which pays out 2 to 1 if the dealer’s face-down card gives them a blackjack. On the other hand, some casinos don’t allow players to surrender their hand in return for half of their initial bet. Generally, though, the rules will be broadly the same wherever you play.

So far, we’ve assumed that it’ll only be you and the dealer sat at the table. In reality, there will likely be other players sat at the table also. However, this doesn’t affect the gameplay. Players play their hands going clockwise from the left of the dealer, just like in poker, and then the dealer plays theirs. I may add a local co-op function at a later date.


The rules have been taken from www.blackjackpractive.co.uk/rules.html
