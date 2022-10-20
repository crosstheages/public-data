# Cross The Ages: TCG Open Beta Patch Notes

## Direct Links

- 0.2.1
  - [Patch](#021-patch)
- 0.2.0
  - [Patch](#020-patch)

## 0.2.2 Patch

`Upcoming`

Changes

- Cards
  - Added illustrator name.

Fixes

- Cards
  - Updated wrong card names.

## 0.2.1 Patch

`2022-10-20 03:00 UTC`

Changes

- Duels
  - Trisel gains have been adjusted retroactively:
    - +30 Trisel for a win.
    - +15 Trisel for a loss in a draw.
    - +10 Trisel for a loss with at least 40% of the cards on the board.
    - +5 Triself for a loss with at least 30% of the cards on the board.
    - Loose due to timeout, surrender or disconnect does not reward any trisel.
  - You can now earn chests to incubate after each win. Keep in mind that your unlocker slots are limited, you can unlock the 2nd and 3rd one by leveling up. 4th to 6th are locked behind Shop Passes that will be enabled later in the Early Access.
- Cards
  - Weekly rotation has been updated, if you had card from the rotation in your deck you have to update it!
  - Added a button to lock/unlock your card in order to avoid accidently using them as reagents on the crafting or trade it.
  - The lock indicator is also available in the card folder view.
  - Added a button to mint your cards, each mint cost you 2 CTA Token. Tokens can be refilled in the shop.
  - Rotation and Training cards are no longer shown in the collection, only in the deck building card selector.
  - Default sort for a card is now: Power > Foil > Numbering.
  - Now show "N/A" as numbering if the card is not owned (training and free rotation cards).
  - Card numbering is now shown in the card folder.
- Shop
  - Added an information box showing the number of packs available to buy and when it will reset. The limit is 167 packs per day.
  - "?" information box has been updated to show the odds of R+ and C+ cards.
- Dashboard
  - Feedback entry now redirect to our website instead of triggering a mail.
  - Added tier 7 and tier 8 in Perks.
- System
  - Added a new way to handle layout and resize, you can now resize the windows as you would like and the game will adjust itself. In fullscreen, you can choose the resolution you want to display the game.
  - Added a version checker at the start of the game, until Launcher is ready you will be warned if you need to download a new version of the game.
  - Some players were able to duplicate their packs by bridging them during the first hour of the Early Access. All the packs, minting passes and cards have been burned and put back in the stock.
  - Users who were not able to open their packs between 5pm UTC and 11pm UTC on the first day and who did not receive the 2 Ultra Rare cards as compensation as it was reserved to those having their packs burned now did received it as airdrop.
  - Standard light field is now available in every chest. The field has been airdropped proportionally to what people would expect to have depending on their openings.
  - Every field has been changed to Uncommon rarity (mostly impacting for Crafting). Keep in mind that they were before considered common, so in the chests from the shop those fields are now counted in the Uncommon section. The description will be updated accordingly later on, drop rate is the same.

Fixes

- Duels
  - Fixed card being stuck under the mouse while having low FPS.
  - 10 seconds timer is now correctly taken in effect for player 1.
  - Header is now shown during the 10 seconds timer.
  - Foil effect and card numbering are now correctly displayed during a duel.
  - Correctly sort the hand after a discard & draw of a card.
- Cards
  - Animation level 1 of some card including Honora have been adjusted.
- Shop
  - Update the text for each card rarity in chest description.
  - You can now buy a chest using Pranas if you have exactly the amount needed.
  - Now correctly display errors encountered in the shop (such as buying over the pack limit).
- Loot
  - Stash has now been renamed to Loot.
  - Chests are sorted based on the number of packs they contain.
- Login
  - Fixed an issue on the activation token due the case.
  - Fixed the scroll sensitivity in the country dropdown.
- Bridge
  - Fixed an issue preventing some packs to be bridge due to missing metadata on Polygon.
- System
  - Fixed currencies (Trisel, Prana and CTA Tokens) being aliased.
  - Fixed cursor size on macOS.

Notes

- Following our [announcement](https://medium.com/cross-the-ages/cross-the-ages-tcg-early-access-game-updates-14e0742b5f9), Legacy packs and Missions are not yet available in this version.
- Launcher (to auto-update the game) is still being worked on.
- In an upcoming update, numbering will be split to separate foil and non-foils as well as each version of the minting passes. This will be done at the same time as we migrate from Stardust collection to Cross The Ages one on IMX.
- After the GA, C+ drop rate will be roughly halved.

## 0.2.0 Patch

`2022-10-12 16:30 UTC`

Initial release of the Early Access.
