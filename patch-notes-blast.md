# Cross The Ages: Blast Patch Notes

## Direct Links

- 0.24
  - [0.24.13554](#02413554-patch)
  - [0.24.13549](#02413549-patch)
  - [0.24.13533](#02413533-patch)
  - [0.24.13306](#02413306-patch)
  - [0.24.13302](#02413302-patch)
  - [0.24.13268](#02413268-patch)
  - [0.24.13257](#02413257-patch)

## 0.24.13554 Patch

`2025-05-25 15:00 UTC`

### Fixes
- General
  - Fixed an issue with the ios build allowing access to menus that were not intended to be accessible, making deck edition not possible.
- Play
  - Fixed a display issue with cards that could get stuck with the cursor on some very specific cases.
- Deck
  - Fixed an issue when selecting a Blast level with an inferior level not selected yet, it would fill the lowest level instead.

### Known issues
- General
  - There is some performance issue on some devices with lags and impossibility to play cards. We are actively working on a setting to reduce effect quality and allow you to play as well as reduce overheating and battery consumption.

## 0.24.13549 Patch

`2025-05-25 08:00 UTC`

### Changes
- Play
  - Disabled capture preview indicator for spectators.

### Fixes
- Play
  - Fixed balance on some field sounds.
- Deck
  - Fixed an issue with the auto-deck being stuck when going back before naming the deck.
  - Fixed the display of steps in auto-deck.
  - Fixed some display issues in the deck edit menu.
  - Fixed deck selection not showing deck color.
  - Fixed deck list not showing decks without blast level 2 and 3.

## 0.24.13533 Patch

`2025-05-25 08:00 UTC`

### Changes
- External test 2
  - Welcome back for the second External test of Blast. As we progress on the development of Blast, we wanted to share our progress to give you a better comprehension of the concept with all planned Blasts for the first release. We listened closely to your feedback and made some adjustments on specific outliers. We want to add other things from your feedback but some of them will take time to develop so stay tuned!
  - You are currently playing on a test environment disconnected from the live server. This means that any actions performed in this environment will have no impact on your main account. In order to allow you to fully test the new gameplay, you have received all the cards directly on your test account.
  - At the end of this second test phase, you will receive a new form to give us your impressions and suggestions. Your feedback is invaluable in helping us improve the game experience.
  - Thank you for your participation, all players who complete a duel during this test phase will receive an exclusive card on their main account.
  - Thank you for your support and enjoy the game!
- Gameplay
  - Blasts
    - 2 new Blasts added
      - Hack
        - Level 1 (50 energy): You can view your opponent's hand.
        - Level 2 (100 energy, 3 charges): You can view your opponent's hand and destroy one card from their hand.
        - Level 3 (200 energy, 1 charge): You can view your opponent's hand and steal a card from their hand to place it directly on the board.
      - Gravitational Wave
        - Level 1 (50 energy): Unleashes a wave of energy on a row or column which pushes the first card encountered in that direction one cell. If the card cannot be moved, it loses -100 power.
        - Level 2 (100 energy, 3 charges): Throw an energy ball onto a cell on the board, which pushes all adjacent cards outwards by one cell. If a card cannot be moved, it loses -100 power.
        - Level 3 (200 energy, 1 charge): Launch a wave from the edge of the board to move all the cards on the board by one cell. If a card cannot be moved, it loses -100 power.
    - 1 Blast updated
      - Drone Command
        - We inverted Drone level 1 and Drone level 2 and updated the energy cost. Here is the full breakdown:
          - Level 1 (75 energy): Allows you to move a card on the board to a different occupied location. The two cards swap positions.
          - Level 2 (200 energy, 3 charges): Allows you to move a card on the board to a different free location.
          - Level 3 (300 energy, 1 charge): Allows you to move a card on the board to a different occupied location. The card occupying that location is then returned to its owner's hand. If the owner's hand is full, the card is destroyed.
    - You can now mix 3 different Blasts levels for your deck.
  - Energy
    - You now regain 500 power per turn.
  - First card immunity
    - From the first playtest, we saw that many players are afraid to place the first card in fear of it being captured directly.
    - To counter this, we added an immunity to captures for the first card played during 1 turn. The card is not immune to Blasts usage.
  - Fields
    - Fields now last 3 turns.
  - Card display
    - We changed the way we display cards, without borders, to better emphasize card control. We are extra curious about what you think about this change, so please send us feedback!
  - Sound
    - Added some sound to the game as well as background music. Keep in mind that this is only a first pass and that not all sounds have been integrated.
- Collection
  - Deck edition
    - We are presenting the new way to edit your decks. You will notice that the style of this new UI is quite different from the other actual screens. This is part of the whole redesign we are currently doing to unify all screens with a coherent and enhanced experience. 
    - This is a big part of our current work charge and we plan to release the rest of the redesign soon for remaining screens.
- Visual changes
  - Added textual value of how much HP was lost beside the avatar when inflicting damage.
  - New visual applied to logs.
  - Added a way to look at the description of the opponent's Blasts by clicking on his energy bar.
- Spectator mode
  - Spectator mode is back in custom mode!

## 0.24.13306 Patch

`2025-04-30 16:00 UTC`

### Fixes
- Play
  - Fixed a visual issue with drone animation (some cards were visible on the side on the board).

## 0.24.13302 Patch

`2025-04-30 12:00 UTC`

This version will be available on Epic Games Store, a link will be send by mail to all whitelisted accounts after the maintenance. 

### Changes
- Play
  - Field cards no longer require power to be played. Their behavior remains unchanged: they still increase the power of all allied cards of the same element for the duration of a single turn.
  - From the second turn onward, the amount of power gained per turn has been increased to +500, while the first turn for each player remains at +0. This adjustment applies during the second week of the Closed Playtest 2.
  - Players can now activate multiple levels of a Blast in the same turn if they have enough power available. It is now possible to use level 1, 2, and 3 Blasts during a single turn if the required power is met, but the level usage limitations remain unchanged.

### Fixes
- Play
  - Fixed a visual issue with card borders not displaying correctly.
  - Mulligan phase can take some time to activate and allow card selection.

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
