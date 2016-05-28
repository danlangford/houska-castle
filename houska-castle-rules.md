# Houska Castle

## Game Type

Single player puzzle game with only a standard deck of cards.

Could also be adapted for multi player co-op or as a mechanic of a D&D/RPG campaign dungeon crawl. 

## Object of the Game

Survive the onslaught of monsters and demons. Discover relics along the way to rejuvinate and empower the Hero. Each turn involves the Hero and monster alternating the play of cards from their limited hand size. Hero wins the encounter when he plays a higher sum of card values.

**TL;DR Fight! Dont Die!**

## Gear

 * Standard Deck w/2 Jokers

_Optionally for some math help_

 * pencil and paper
 * calculator
 
## Setup

 1. Place face up on the table:
    * the King of Hearts (**The Hero**)
    * the two jokers (**Hero Points**)
    * a single 5 value card, any suit (**Max HP**)   
 2. Shuffle the remaining 50 cards.
 3. Split the cards making two draw piles of ~25 cards. A `Monster Pile` and a `Combat Pile`.
 4. Draw 5 cards from top of `Combat Pile` into your `Hand`. These represent your initial 5 HP. Full hand is full HP and empty hand is death.
 
_**Fig.1** initial game setup_

    MONSTER                         COMBAT
    |XX|                              |XX|
    
    
    
    HERO: Kh JK JK 5s HAND: 2h 2s 4d 6c 9h


## Turn Overview

 * **Reveal Monster** Reveal top card on the `Monster Pile`. 
 * **Make Observation** Move 2 cards from the top of the `Combat Pile` to the field. This will be the monsters initial attack. Reveal 1 of them. This observation will help you guage how your initial encounter with this monster may play out.

_**Fig.2** monster encounter with observation_

     MONSTER                         COMBAT
     |XX| 5c                     ?? 3c |XX|
     
     
     
    HERO: Kh JK JK 5s HAND: 2h 2s 4d 6c 9h


 * **Combat Phase** Alternate playing cards from `Hand` as the Hero and the monsters cards off top of `Combat Pile` until combat is resolved (meaning: you play a larger sum of card values + buffs than the monster). See the section on the Combat Phase for details.
 * **Clean Up** Shuffle together all the cards involved in combat and the monster you (presumably) defeated placing all these cards at bottom of `Combat Pile`. 
 * **HP Regen** You may draw up to 2 cards from the top of the `Combat Pile` into `Hand`. Your hand size may never exceed your Max HP (5 at the start of the game.)
 
 _Note:_ you lost a few cards in the fight. This represents HP that you lost. You regen 2 HP (in the form of card draw) each turn. Efficient battle would be defeating each monster with 2 cards. Good luck with that.
 
## Combat Phase

The combat phase consists of the following steps

 1. **Hero plays card** from `Hand`. On the initial attack the Hero can play two cards. 
 2. **monster plays card** from top of `Combat Pile`. Initial attack will be with 2 cards, 1 of which was revealed already as an observation.
 3. **determine attack strength** of Hero and monster by summing the card face values. The Hero is looking to tie or beat the monster. J=11, Q=12, K=13. Since your Hero is the King of Hearts your **Heart cards have +2** buff to their face value. 
 4. proceed:
    * If Hero points >= monster points then the monster is defeated; proceed to Clean Up and HP Regen (even if Hero Hand is empty, you barely survived my friend).
    * If Hero hand is empty the Hero is defeated. `Game Over`
    * If Hero points < monster points then repeat from Step 1
    
_Note:_ Monsters face value determines how many cards the monster can play and is not considered when calculating points for the monster.  Card value acts as the monsters HP Pool or sustainability. When monster `3d` can only play 3 cards (2 inital attack + 1 more) however the Hero can continue to play until the Hero's points exceed the monster points or the Heros hand (aka HP pool) is depleated.

## Examples

_**Fig.3** Hero plays initial attack_

    MONSTER                         COMBAT
    |XX| 5c                     ?? 3c |XX|
    
                                6c 2h
    
    HERO: Kh JK JK 5s HAND: 2s 4d 9h __ __


_**Fig.4** monster finishes initial attack, points tallied, Hero is victorious_

    MONSTER                         COMBAT
    |XX| 5c      6+3=9 Points   6d 3c |XX|
    
            6+(2+2)=10 Points   6c 2h
    
    HERO: Kh JK JK 5s HAND: 2s 4d 9h __ __


_**Fig.5** game state after clean up and 2 hp regen_

    MONSTER                         COMBAT
    |XX|                              |XX|
    
    
    
    HERO: Kh JK JK 5s HAND: 2s 4d 8c 9h Tc


_**Fig.6** second monster encounter with observation_

    MONSTER                         COMBAT
    |XX| 4c                     ?? Th |XX|
    
    
    
    HERO: Kh JK JK 5s HAND: 2s 4d 8c 9h Tc

## Royalty

The Royalty cards have the following face values: J=11, Q=12, K=13. They also have some very special side effects.

**TL;DR:**

 * Jacks nullify opponents lowest card.
 * Queens steal opponents next card played.
 * Kings bring another card into battle (from top of `Combat Pile`)

### Jacks

Jacks have the ability to counter attacks nullifying the damage. When a Hero plays a Jack from his `Hand` or a monster plays a Jack from the `Combat Pile` then their respective opponents lowest card is flipped over. The flipped card does NOT count towards points but does still count towards the number of cards a monster has played. (Remember a monsters face value determines how many cards they can play.)

When a Jack appears in the `Attack Pile` or as the first card flipped during an observation when the Hero has no cards in play this ability has no effect.

### Queens

A queen is sneaky, charming and seductive. When a Queen is played from the Hero `Hand`, the `Combat Pile` or appears in the `Monster Pile` then the NEXT card to be played by the opponent will be charmed by the queen and change alliance. Move this card to the other side of the conflict.

The stolen card DOES NOT count as a card "played" by the monster in respect to how many cards they are allowed to play. As a result you should place the card under the Queen to represent that they Queen stole it. The stolen card DOES however count towards the point value when calculating for defeat.

A card stole from a Hero to the monster will lose all buffs. Cards stolen from a  monster to a Hero will gain buffs if applicable. If a Queen is played but cleaned up before the ability is triggered then the ability is LOST and the next card the opponenet plays will not change alliance.

### Kings 

Kings are strong and bring body guards along. When a King is played then another card is drawn from the top of the `Combat Pile` and immediatly placed into the field. Place this card below the King to show this effect.

The new card DOES NOT count as a card played for the monster. It DOES count towards the monsters points. If a King appears as a monster from the `Monster Pile` then it results in the Kings initial attack being 3 cards with the first 2 of them being observed. In this scenario a Hero is still limited to playing only two cards. If a Hero plays a King on the initial attack the new card does not count towards the Heroes 2 card limit on initial attacks.

## Ace Artifacts

The Aces are powerful artifacts that replenish and empower the Hero. When an Ace is drawn from the `Combat Pile` the player "Levels Up" by doing the following:

 * Increment the **Max HP** card. Find the new card in the `Combat Pile` if possible. Place the old card at the bottom of the `Combat File`.
 * Heal to full HP by drawing from the top of the `Combat Pile`. Take into consideration your new **Max HP**
 * Shuffle very well and piles that were observed while locating the new Max HP card.
 * Place the Ace Artifact near to the Hero card.
 
Also, going forward, the Heros **cards that match the artifact suit have a +1 buff** (this means that once the Ace of Hearts Artifact is collected your Heart cards now have +3 buff)

If an Ace is drawn from the `Monster Pile`, or from the `Combat Pile` during a monster draw you will place the Artifact beneath the monster and it will become a reward for defeating the monster. These cards do not count towards the monsters played card limit so draw another if needed. Artifacts do not buff a monsters attack cards. Once the Hero defeats the monster and collects the Artifact as a prize then the Artifacts powers take effect and the Hero "Levels Up".

_**Fig.X game state after the second Artifact is discovered**_

    HERO: Kh JK JK 7s Ac Ah HAND: 3d 5d 7c 8h 8s 9d 9c

## Jokers (Hero Points) and Death

At any time the Hero may use a Hero Point by playing a Joker. This grants the Hero a full Heal to Max HP. This can be performed immediatly after the Hero has played the final card from hand thus barely cheating death. This can only be done twice (once per Joker) in the entire game and when played the Joker is flipped over or set aside not to be used again. 
 


