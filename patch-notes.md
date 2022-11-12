# Cross The Ages: TCG Open Beta Patch Notes

## Direct Links

- Upcoming
  - [Upcoming](#upcoming)
- 0.2.5
  - [0.2.5b](#025b-patch)
  - [Patch](#025-patch)
- 0.2.4
  - [Patch](#024-patch)
- 0.2.3
  - [Hotfix 1](#023-hotfix-1)
  - [Patch](#023-patch)
- 0.2.2
  - [Patch](#022-patch)
- 0.2.1
  - [Hotfix 1](#021-hotfix-1)
  - [Patch](#021-patch)
- 0.2.0
  - [Patch](#020-patch)

## Upcoming

`TBD`

Changes

- Duels
  - Trisel and Exp gains have been adjusted to let you earn more under some circumstances:
    - You get an extra 10 Trisel / 100 EXP if you own more than 90% of the board on a win.
    - You get more Trisel and EXP on your wins based on your rating. Thresholds are at 1150 / 1500 / 1850 / 2200 / 2550. For each threshold you have +5 Trisel / +50 EXP per win.
- Cards
  - Honora & Hannibal is now correctly displayed as Special Rare (was Rare before).
    - Note: NFT version will be changed after migration.
  - Hanzo & ValRed is now correctly displayed as Rare (was Uncommon before).
  - Nox & Skeleton is now correctly displayed as Ultra Rare (was Uncommon before).
- Loots
  - Reward, Daily and Weekly chests can now contain foil cards.

## 0.2.5b Patch

`2022-11-09 20:45 UTC`

Fixes

- Loots
  - Reward chest opening should no longer be stuck.

## 0.2.5 Patch

`2022-11-09 17:00 UTC`

Changes

- Loots
  - Legacy packs are now available for opening, it will be enabled on 2022-11-09 @ 19:00 UTC.
  - Chest opening animation can now be skipped.
- Crafting
  - Awakening is now available, it will be enabled on 2022-11-10 @ 17:00 UTC.
- Cards
  - Free mint (if you have any) is now used instead of CTA Tokens.
- Missions
  - A new mission has been added, it requires you to unlock instead of open chests.

Fixes

- Profile & Settings
  - Various fixes
- System
  - Game should now be able to connect to the internet on older versions of macOS.

## 0.2.4 Patch

`2022-11-05 10:00 UTC`

Changes

- Duels
  - Power Mirror SA now dynamically show the expected power on your leader during gameplay.
    - Note: The correct value for now is only during your turn, we will update it later on.
  - Logs now display if the host changed the rules of who starts on Friendly Duel.
  - Matchmaking now finds an opponent near your rating more efficiently. After the 90s it is still random.
  - Added a new VFX for affinities. Color change based on if simple or double.
  - Tile colors have been updated to make it more clear based on the field currently active.
- Loots
  - Reward chest unlocker slots #4 to #6 are now available depending on the presale pack you opened until the end of the EA. In the GA, they will be available by buying an item in the Shop (Shop Passes).
  - Reward chest can now be converted to Trisel instead of being opened at a rate of 1h = 10 Trisel. It means you will not get the cards inside it but Trisel in exchange, this feature is available after the time needed to unlock. All slots (including the free #1 to #3) are eligible for this convert mechanism.
    - Considering we added the reward chest convert feature and that Shop Passes give 3 more unlock slots, there will not be a new daily mission for Shop Passes owners as it is now backed into the convert mechanism.
  - Unlock and Open screens have been merged into a screen.
  - Slot #3 is now enabled after 50 unlock, no matter if you open or convert the chests.
- Missions
  - Reset timers are now displayed.
- Settings
  - You can now choose the intensity of the foil effect, both in menus and in-game.
- Login
  - It is no longer possible to use the username, only the email is now valid.
- System
  - You can now make a long left-click to emulate the behavior of a right-click.

Fixes

- Duels
  - Player remaining time correctly shows what is set in Friendly Duel.
  - Foil effect is now correctly displayed on animated cards.
  - Foil effect is now correctly displayed on opponent cards.
- Missions
  - Login mission is now completed whenever you access the missions, you no longer have to relog.

## 0.2.3 Hotfix 1

`2022-11-01 23:30 UTC`

Changes

- Missions
  - Added a new mission (both with daily and weekly objectives), its objective is related to the amount of cards captured during ranked duels.
  - Added 3 new weekly missions (total is now 24). Win and Capture X in a single turn T1 and T2 now rewards half completion %. It means you need to do at maximum 23 of the 24 missions available to unlock weekly T3. Also you now have +240 Trisel per week that way.
  - Update various objectives.

Fixes

- Duels
  - Matchmaking conditions are now correctly checked for both players.
- Crafting
  - Field cards now correctly require 10 cards to be merged like other uncommon cards.
- Missions
  - Capture X in a single turn advancement now only shows you 0 / X until you complete it.

## 0.2.3 Patch

`2022-10-28 23:45 UTC`

Fixes

- Duels
  - SA Mirror Power now correctly displays its VFX when played.
  - SA Power Stacking icon has been changed.
- Cards
  - Display of cards on Crafting / Collection / Decks has been adjusted to show intended cards depending on the context.
  - Deck power computation is now working again as intended.
- Missions
  - Fields missions are now correctly computing the advancement.
  - Win with more than 120s and 70% of possession are now correctly counting win only (before was counting any game).
  - Weekly progress bar display has been adjusted.
- Profile
  - Highest rating value has been fixed.
- System
  - Halloween ambiance sound has been adjusted.
  - Various text adjustments in French.

## 0.2.2 Patch

`2022-10-28 03:30 UTC`

Changes

- Launcher
  - A launcher has been deployed. It is now the main way to access the game, it will update itself as well as the game so no more manual download needed.
  - Keep in mind that this is the first iteration, many things will be added to it in the future.
  - Also it is the first release, so if you encounter any issue with it, do report it! For macOS there is an Intel and an M1/M2 version.
- Duels
  - Experience gains have been adjusted retroactively:
    - +300 experience for a win.
    - +150 experience for a loss in a draw.
    - +100 experience for a loss with at least 40% of the cards on the board.
    - +50 experience for a loss with at least 30% of the cards on the board.
    - Loss with less than 30%, due to timeout, surrender or disconnect does not reward any experience.
  - Coin toss algorithm now uses a cryptographic implementation for its RNG non-subject to modulo bias. What that means is that you are less likely to see a streak.
  - In addition to this, your recent games weigh the coin toss to let you converge to a 50/50 faster in case you were unlucky (bad luck protection system).
    - Note: We are internally iterating on changes to make the difference between starting or not a game less of a burden.
  - Rating system have been adjusted as follow:
    - Everyone starts at 1200, for players with existing rating prior to this patch you will see your real rating instead of a number starting from 0.
    - You are immune to rating loss for the first 10 games.
    - Adjustment factor (K-factor) has been changed to be less punitive until the player reaches higher ratings. New accounts and low-rated players now share the same factor, which means it reduces the incentive to play an alt account.
  - Matchmaking has been changed to increase the odds to meet a player close to your rating. After the 90s it is random.
  - A new SA has been added. It allows you to refill one draw (up to 3) per turn with your Leader on the board and under control.
  - Updated light card drop VFX.
- Cards
  - Free rotation has been updated, and the total number of cards available has been reduced from 31 to 10.
  - Cards that you do not have yet in your collection are displayed in gray.
  - Deck import/export strings now include the power of the card. If there is no match, we take the closest one available.
  - Added illustrator name under the card in detail view.
  - Added animation level 1 for Honora & Hannibal
  - Card details have been updated.
- Shop
  - Neo Halloween chest has been added, it will be available for 2 weeks only.
  - Cards obtained during an opening are now correctly sorted/grouped together.
- Loot
  - Unlocker slot #2 and #3 can now be unlocked after being level 20 or having opened 50 chests.
  - A notification will be shown if you have a chest to unlock or to claim.
- Crafting
  - Potential merge has been unlocked. Keep in mind that it is the first iteration so you might experience some issues, be ultra careful as once merged cards are burned, double check before validating.
    - Note: UI is currently limited to 3 cards and selector re-use the one from the collection. In a future update you will be able to do it in bulk.
    - Known issue: Some non-foil common cards might not be given as a choice to merge.
  - Alternative Combo now correctly applies the +20 power from Alternative.
    - Note: Honora + Hannibal is the only Alternative Combo card obtained by player right now, its power has been increased by 20, from 660 to 680.
- Missions
  - Daily and Weekly missions have been unlocked. Missions are randomly chosen every day/week but the same for everyone. This will stay like this until we are happy with their balance, then they will be random for each player.
- Profile
  - Updated the forgotten password workflow.
  - Added a way to update the email linked to the game account.
  - Added the highest rating achieved during the era.
- Social
  - You can now tweak the value for double affinity.
  - You can now decide how the coin toss will be done (randomly, host starts, guest starts).

Fixes

- Duels
  - Dragging of the card should be more stable on all platforms.
  - Right panel buttons now cancel each other.
  - Queuing while being in-game will reconnect you to the game.
- Cards
  - Updated card names & illustrators.
  - Honora & Hannibal is now correctly displayed as Special Rare (was Rare before).
- Shop
  - Various texts have been adjusted.
- Profile
  - Win rate is now shown with two decimals.
- Bridge
  - Fixed another issue preventing some packs to be bridged due to missing metadata on Polygon.
- System
  - macOS executables are now fully signed and notarized to Apple.

## 0.2.1 Hotfix 1

`2022-10-21 02:30 UTC`

Fixes

- Cards
  - Weekly rotation is now available for players who used rotation card as leader or with empty decks. Once you login, the rotation cards should be available. Note that since 0.2.1 patch, rotation cards are displayed only in card selection when building a deck not in the collection.

## 0.2.1 Patch

`2022-10-20 03:00 UTC`

Changes

- Duels
  - Trisel gains have been adjusted retroactively:
    - +30 Trisel for a win.
    - +15 Trisel for a loss in a draw.
    - +10 Trisel for a loss with at least 40% of the cards on the board.
    - +5 Trisel for a loss with at least 30% of the cards on the board.
    - Loose with less than 30%, due to timeout, surrender or disconnect does not reward any trisel.
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
- Dashboard
  - Now correctly refresh your Trisel / Prana / CTA count whenever you enter it (before it was only in the shop).
- Loot
  - Stash has now been renamed to Loot.
  - Chests are sorted based on the number of packs they contain.
- Login
  - Fixed an issue on the activation token due the case.
  - Fixed the scroll sensitivity in the country dropdown.
- Bridge
  - Fixed an issue preventing some packs to be bridged due to missing metadata on Polygon.
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
