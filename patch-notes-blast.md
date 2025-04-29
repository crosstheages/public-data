# Cross The Ages: Blast Patch Notes

## Direct Links

- 0.24
  - [0.24.13302](#02413302-patch)
  - [0.24.13268](#02413268-patch)
  - [0.24.13257](#02413257-patch)

## 0.24.13302 Patch

`2025-04-30 08:00 UTC`

This version will be available on Epic Games Store, a link will be send by mail to all whitelisted accounts after the maintenance. 

### Fixes
- Play
  - Fixed a visual issue with card borders not displaying correctly.
  - Mulligan phase can take some time to activate and allow card selection.

### Changes
- Play
  - Field cards no longer require power to be played. Their behavior remains unchanged: they still increase the power of all allied cards of the same element for the duration of a single turn.
  - From the second turn onward, the amount of power gained per turn has been increased to +500, while the first turn for each player remains at +0. This adjustment applies during the second week of the Closed Playtest 2.
  - Players can now activate multiple levels of a Blast in the same turn if they have enough power available. It is now possible to use level 1, 2, and 3 Blasts during a single turn if the required power is met, but the level usage limitations remain unchanged.

### Known issues
- All sounds have been disabled until Closed Playtest 2.

## 0.24.13268 Patch

`2025-04-23 08:00 UTC`

### Fixes

- Collection
  - Fixed the blast selection missing some assets.
- Dashboard
  - Fixed the patch notes window being empty.
- Gamemode selection
  - Fixed deck selection not being refreshed after a deck has been altered and became unusable.
- Play
  - Fixed a display issue with discarded cards with a click showing card borders with no card for a short time.
  - Fixed a display issue with destroyed cards showing transparent cards during animation.
  - Fixed discard zone being misplaced on mobile.

### Known issues

- Play
  - Mulligan phase can take some time to activate and allow card selection.
- All sounds have been disabled until we make a pass on sound integration.

## 0.24.13257 Patch

`2025-04-22 13:00 UTC`

### Changes

- External Test 1
  - Thank you for joining the Blast adventure during this external test phase. We would like to inform you that, for this test phase, only essential gameplay features will be available. Side menus and other content are not yet available. Please note that the game is still under development, and you may encounter bugs or unexpected behavior: animations, sounds, visual effects and other features may be missing, and will be added as development progresses.
  - You are currently playing on a test environment disconnected from the live server. This means that any actions performed on this environment will have no impact on your main account. In order to allow you to fully test the new gameplay, you have received all the cards directly on your test account.
  - For the first external test, only two Blasts are available: Fireball (Arkhante's Blast) and Drone Command (Mantris' Blast).
  - At the end of this test phase, you will receive a form to give us your impressions and suggestions. Your feedback is invaluable in helping us improve the game experience.
  - Thank you for your participation, all players who complete a duel during this test phase will receive an exclusive card on their main account.
  - Thank you for your support and enjoy the game!
- Gameplay
  - The point system has been replaced with a health system. Both players start with 25,000 Health points. The goal is to reduce the opponent's health to 0.
  - Players inflict damage to the opponent at the end of their turn up to the sum of the power of the cards you control.
  - Special Abilities are replaced by Blasts. Blasts have 3 levels. When you choose a Blast for your deck, you choose all 3 levels, and you can play all 3 levels during the game. You can only play one Blast per turn.
  - Each level of Blast has different effects, different energy costs, different max uses.
  - We added an Energy system for playing cards and Blasts. You start with 650 energy and regain 350 energy at the start of each turn. The cost to play a card is equal to its power.
  - You can play several cards per turn as long as you have enough energy.
  - You can have as many field cards as you like in your deck. The cost to play a field card is equal to its power. Field cards only last for the duration of the player's turn. Only one field can be active at a time.
  - You can discard & draw several times per turn. The first is free, but subsequent discards cost 200 Health points.
  - We removed the Trinity system. (But affinity remains).
  - We removed the double advantage/disadvantage in the heptagram. Now an element is only strong against 1 other and weak against another. Also changed the order of the Heptagram to keep it logical.
  - Captures are only made with a chain of 1.
  - If a card on the board drops to 0 power or less, it is destroyed.
  - You can only have a maximum of 6 cards in your hand at any time. If you draw a 7th card, it is destroyed.
  - Players have 60 seconds to play their turn. If you don't play during your turn, your turn ends automatically. For your next turn you will have only 30 seconds to play your turn. If you don't play during your turn, your turn ends automatically. For your next turn you will have only 15 seconds to play your turn. If you don't play during that turn, you lose the duel. Playing something during a turn with reduced time puts back your turn duration at 60 seconds.
  - Win conditions are: 
    - Reduce opponent's health to 0,
    - The opponent doesn't have a card in his deck and has to draw,
    - The board is filled and player has more health than the opponent,
    - The opponent didn't play within the allowed time 3 times in a row.
- Blasts
  - Fireball
    - Level 1 (50 energy): Permanently weakens a card by -100 power.
    - Level 2 (100 energy, 3 charges): Permanently weakens a card by -200 power. Opponent's cards on adjacent squares each lose -100 power permanently.
    - Level 3 (200 energy, 1 charge): Destroys a card. All other opponent's cards on the board lose -100 power permanently.
  - Drone Command
    - Level 1 (150 energy): Allows you to move a card on the board to a different free location.
    - Level 2 (250 energy, 3 charges): Allows you to move a card on the board to a different occupied location. The two cards swap positions.
    - Level 3 (300 energy, 1 charge): Allows you to move a card on the board to a different occupied location. The card occupying that location is then returned to its owner's hand. If the owner's hand is full, the card is destroyed.
