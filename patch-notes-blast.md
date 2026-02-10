# Cross The Ages: Blast Patch Notes

## Direct Links

- 0.24
  - [0.24.15825](#02415825-patch)
  - [0.24.15479](#02415479-patch)
  - [0.24.15475 Hotfix #1](#02415475-hotfix-1)
  - [0.24.15475](#02415475-patch)
  - [0.24.15472](#02415472-patch)
  - [0.24.15464](#02415464-patch)
  - [0.24.15129](#02415129-patch)
  - [0.24.15101 Hotfix #2](#02415101-hotfix-2)
  - [0.24.15101 Hotfix #1](#02415101-hotfix-1)
  - [0.24.15101](#02415101-patch)
  - [0.24.15087 Hotfix #2](#02415087-hotfix-2)
  - [0.24.15087 Hotfix #1](#02415087-hotfix-1)
  - [0.24.15087](#02415087-patch)
  - [0.24.14788 Hotfix #1](#02414788-hotfix-2)
  - [0.24.14788 Hotfix #1](#02414788-hotfix-1)
  - [0.24.14788](#02414788-patch)
  - [0.24.14777 Hotfix #1](#02414777-hotfix-1)
  - [0.24.14777](#02414777-patch)
  - [0.24.14751](#02414751-patch)
  - [0.24.14734](#02414734-patch)
  - [0.24.14716](#02414716-patch)
  - [0.24.14675 Hotfix #1](#02414675-hotfix-1)
  - [0.24.14675](#02414675-patch)
  - [0.24.14618 Hotfix #2](#02414618-hotfix-2)
  - [0.24.14618 Hotfix #1](#02414618-hotfix-1)
  - [0.24.14618](#02414618-patch)

## 0.24.15825 Patch

`2026-02-11 08:00 UTC`

### Changes

- Lunar New Year event
  - A special event is available for the Lunar New Year!
  - The event will last until `2026-03-11 08:00 UTC`
  - This event brings a whole new gamemode specific to this event: 
    - You have in hand a spell card, usable at any time.
    - By spending energy and placing cards on the board, you can level it up to enhance its effects.
    - When used, its effect activates and then the card is discarded; you then draw a new level 1 card at the next turn.
    - Use your power strategically to overcome your opponents!
  - When winning event duels, you have a 50% chance to drop a Pietro Exclusive card! It has a 80% chance to be standard and 20% chance to be alternative. They are static and have a chance to be auto minted depending on your Mint Pass (Red Mint Pass 0.005%, Green Mint Pass 0.010%, Blue Mint Pass 0.020%, Legacy Mint Pass 0.035%, Golden Mint Pass 0.050%, Golden Legacy Mint Pass 0.065%).
  - Win duels to unlock exclusive cosmetics only unlockable during this event.
  - All cosmetics are also available in the Shop. The cosmetics available in the shop are the same as the ones you get while playing. If you buy the pack and already have some of the cosmetics, the price is not reduced and you won't get the cosmetics you already had.
  - The special Lunar New Year gamemode also gives Ark and unlocker chests at the same rate as a Silver rank player in ranked. It doesn't drop Exclusive Leaderboard cards.
- Gameplay
  - Following feedback about the location of the discard area, it has been moved to the left side of the screen to avoid an unintentional end of turn.
  - Improved card movement and many Blast animations and feedback.
  - Added a glow around the endturn button to better emphasize the current player.
- Balancing
  - Blast: Drone Command
    - Level 3 complete redesign: 
      - Full description: Move a controlled card on the board to a free location and restart an attack.
      - Cost: 400 Power (up from 250).
  - Blast: Gravitational Wave
    - Level 1 now strictly applies its current description and only moves the first card encountered:
      - Full description: Unleashes a wave of energy on a row or column which pushes the first card encountered in that direction one cell. If the card cannot be moved, it loses -50 power.
      - Cost: 75 Power (down from 100).
    - Level 2 now strictly applies its current description and only moves cards adjacent to the selected cell:
      - Full description: Throw an energy ball onto a cell on the board, which pushes all adjacent cards outwards by one cell. If a card cannot be moved, it loses -100 power.
  - Blast: Hack
    - Level 1 complete redesign: 
      - Full description: Choose a card from your opponent's hand that they cannot play on the next turn. You cannot choose the same card on the following turn.
      - Cost: 75 Power (up from 25).
    - Level 3 complete redesign: 
      - Full description: The initial cost of enemy Blasts is multiplied by 4 during the next turn, then by 2 during the following turn. It returns to normal starting from the third turn.
      - Cost: 250 Power (down from 500).
  - Blast: Draw of Fate
    - We inverted level 1 and level 2 to limit the draw cards usage.
    - Level 1 also reduced the number of cards seen:
      - Full description: Reorder the top 2 cards of your deck.
      - Cost: 100 Power (down from 125).
    - Level 2 
      - Full description: Draw 1 card without triggering overdraw.
      - Cost: 125 Power (up from 100).
    - Level 3 complete redesign:
      - Full description: Look at the top 5 cards of your deck, then choose one. The 5 cards are then shuffled, and you draw them without triggering the overdraw until you draw the chosen card. You regain 100 power for each card not drawn.
      - Cost: 200 Power.
  - Rune: Explosive
    - Complete redesign: Explosive rune now empowers the card you play but only when you play it to make attacks.
    - Full description: This card gains +25/50/100 additional power until the end of the capture.
  - Rune: Overpowering
    - This rune can now be played on opponent's cards as well as controlled cards.
- Inventory
  - Increased the odds for bonus cards of old collections to reflect the odds chance of the booster it comes from. It increases chances for mythic cards for higher tier unlocker boosters.
- Pranah bundles
  - The last Pranah bundles have been automatically opened and converted into Eternal Stones.
  - Here is the detail for each bundle : Small Pranah bundle: 14 Eternal Stones, Medium Pranah bundle: 67 Eternal Stones, Large Pranah bundle: 190 Eternal Stones, Massive Pranah bundle: 462 Eternal Stones, Huge Pranah bundle: 779 Eternal Stones, Mega Pranah bundle: 1587 Eternal Stones, Giga Pranah bundle: 3968 Eternal Stones, Ultimate Pranah bundle: 7936 Eternal Stones, Golden Pranah bundle: 7936 Eternal Stones, Golden Legacy Pranah bundle: 7936 Eternal Stones.
  - Users that still had Pranah from bundle opening have been awarded Eternal Stones.
- Shop
  - Added step options for converting Trisel and Eternal stones.
- Collection
  - Following feedback, we have added the name of the artist who worked on the card animation when the full display of a card with an animated skin is selected.
- Authentification
  - We added silent authentication with Epic Games (connecting directly to a linked account without additional input). Google and Apple Silent Auth will be implemented in the next patch.
- Deck edition
  - Redesigned the deck Boxes for a more unified theme.  
- Profile
  - Added a redirection to the portal for username changes.
- Misc
  - Improved some UI inconsistencies in authentication, dashboard, collection, profile, inbox, leaderboard screens.
  - Improved the way we display tooltips when gaining random cards to be more precise.
  - Added the system message to the authentication screen allowing us to better communicate when there are infrastructure issues.

### Fixes

- Gameplay
  - Fixed an issue with capture preview calculation with affinities.
- Leaderboard
  - Fixed an issue with Leaderboard ranking not properly displaying rank changes.
- Inventory
  - Fixed an issue with chests from previous seasons not correctly playing the opening video.
  - Fixed an issue with the booster size when opening a booster.
- Collection
  - Fixed an issue with filters not showing all cards when filtering by rank/grade and not possessed cards (ie: showing all missing grade S cards).
  - Fixed an issue with the skin list showing up multiple times when going back to a previously shown card.
- Misc
  - Fixes an issue with emote resolution not being consistent.

## 0.24.15479 Patch

`2026-01-15 15:00 UTC`

### Fix

- Shop
  - Fixed an issue with purchases not going through on iOS and Android devices.

## 0.24.15475 Hotfix #1

`2026-01-12 08:00 UTC`

### Fix

- Collection
  - Fixed an issue with newly released SR cards not appearing in card stacks.

## 0.24.15475 Patch

`2025-12-17 20:00 UTC`

### Fixes

- Gameplay
  - Fixed an issue with the power shown on a card on the board after swapping possession while having an affinity.

## 0.24.15472 Patch

`2025-12-17 16:00 UTC`

### Fixes

- Event
  - Fixed an issue with event mission progression not counting (Hotfix already live).
- Gameplay
  - Fixed a display issue with cards that have an animation level as skin appearing as invisible in your hand and on the board.
  - Fixed an issue with "too soon to surrender" popup not showing.
  - Fixed a display issue with the unlocker won at the end of a ranked duel showing up twice.
- Merge
  - Fixed a display issue with cards on the merge screen.
- Collection
  - Fixed an issue in the global collection display not loading past the initial loading.
  - Fixed an issue with the collection mission for Dawn of War at 100% not validating (Hotfix already live).

## 0.24.15464 Patch

`2025-12-17 08:00 UTC`

### Changes

- Christmas event
  - A special event is available for the winter season!
  - The event will last until `2026-01-14 08:00 UTC`
  - This event brings a whole new gamemode specific to this event: 
    - At the end of every 3 turns, an elfin drone flies across the board and drops a gift.
    - If the cell it lands in is occupied, it immediately gives a random bonus to the card; otherwise, the gift waits until a card lands on it.
    - The drone's flight path is announced in advance, but the cell it lands on is random.
    - Get all the gifts to overcome your opponent!
  - When winning event duels, you have a 50% chance to drop a Red Tipped Crane Exclusive card and its combo with Garth! It has a 80% chance to be standard, 15% chance to be alternative and 5% chance to be combo. They are static and have a chance to be auto minted depending on your Mint Pass (Red Mint Pass 0.005%, Green Mint Pass 0.010%, Blue Mint Pass 0.020%, Legacy Mint Pass 0.035%, Golden Mint Pass 0.050%, Golden Legacy Mint Pass 0.065%).
  - Win duels to unlock exclusive cosmetics only unlockable during this event. Additionally, event missions now give bonus Ark.
  - All cosmetics are also available in the Shop. The cosmetics available in the shop are the same as the ones you get while playing. If you buy the pack and already have some of the cosmetics, the price is not reduced and you won't get the cosmetics you already had.
  - The special Christmas gamemode also gives Ark at the same rate as a Silver rank player in ranked. It doesn't drop Exclusive Leaderboard cards.
- Balancing
  - Please note that this is a temporary balancing while we do more in-depth changes for next event.
  - Hack level 3 costs 500 Energy (up from 350).
- Eternal Multiplier changes
  - Eternal Multiplier no longer applies to Ark earned at the end of a duel.
  - Rank from Leaderboard no longer increases the amount of Ark earned at the end of a duel.
  - Eternal Multiplier now applies to Ark obtained from Reward Chests.
  - Rank now increases the chance of obtaining higher-tier unlocker chests.
  - Unlocker Chests can only be obtained from winning Ranked duels.
  - Previously unlocked Reward Chests have been automatically obtained to avoid mixing old and new content. All cards and currency have been added to your account.
  - Ark rewards from duels, and unlocker chests have been rebalanced to keep the overall impact neutral for most players.
  - A new effect, Trisel Infusion, has been introduced: every dollar spent in the shop (in CTA Token or Fiat currency) grants one Ranked win that awards 500 Trisel (e.g., spend $10, get 10 infused wins).
  - Trisel Infusion is also available as a VIP Tier 4 item in the Echo Shop on the Portal.
- Shop
  - We enabled CTA Token purchases in the shop.
  - For Android and Apple devices, we added a retry function if the purchase was not successful to retry it the next time you enter the shop so users don't get stuck.
- Unlocker
  - We changed the art of the unlocker display to better match the result and the amount of booster obtained.
- Opening
  - Improved the visual and sound effects of the booster opening.
- Leaderboard
  - Allow the click on other players to display their profile.
- Gameplay
  - Don't show the card detail of cards when selecting a rune and the press is a bit too long.
- Collection
  - Improved some UI in product and Card details.
  - Improved the Blast selection for the deck edition.
- Bug report
  - when reporting an issue from the login page, we added a mandatory email inpu so the support can contact you back.
- Misc
  - Improved some icon resolution.

### Fixes

- Inventory
  - Fixed an issue with Eternal Pranah bundle missing assets.
- Dashboard
  - Fixed an issue with the Dashboard BGM not playing when entering the game.
  - Fixed some asset and font inconsistency.
- Collection
  - Fixed an issue with the deck name change sometimes not registering on PC.
- Reward
  - Fixed some asset and font inconsistency.
- Shop
  - Fixed some asset and font inconsistency.
- Leaderboard
  - fixed a few display issues with the Leaderboard.
- Profile
  - Fixed an issue with some success not being claimable if a higher threshold was already claimed.

## 0.24.15141 Patch

`2025-11-13 16:00 UTC`

### Changes

- Event
  - The event has been extended until `2025-11-26 08:00 UTC`.
  - A notification has been added on the dashboard when a mission is claimable.

### Fixes

- Card
  - Fixed a display issue with Albéris card standard and alternative art being inverted.
  - Fixed an issue with Garth Exclusive missing its artist.
  - Fixed a display issue with some card resolution.
- Gameplay
  - Fixed an issue with Halloween game mode allowing surrender before turn 9.
  - Fixed an issue with the opponent end turn timer sometimes not showing if the device was not at the correct time.
  - Fixed an issue with Draw of Fate level 3 and Hack level 3 being able to select a card slot occupied by a pumpkin and locking the use of the Blast.
  - Fixed a display issue with cards that could get stuck at the center of the board in case the timer expired while playing the card.
  - Fixed a display issue with the health not refreshing properly after a quick end turn.
  - Fixed an issue at the end of a duel locking the player on an empty board.
  - Fixed an issue with Hack 2 and 3 still showing after a reconnection following a swapturn (hotfix already live).
  - Fixed a display issue with damage display after a card has been destroyed by a pumpkin creation (hotfix already live).
- Collection
  - Fixed an issue with the mint cost display.

## 0.24.15101 Hotfix #2

`2025-11-04 15:00 UTC`

### Change

- Halloween
  - Removed the mmr restriction in the halloween game mode to reduce queue time.

### Fixes

- Gameplay
  - Fixed an issue that prevented the use of gravitational wave on specific case in the Halloween game mode.
  - Fixed an issue that removed roots when a card was played beside another controlled card in the Halloween game mode.
- Lobby
  - Fixed an issue with Custom lobby not showing 75s per turn option (same as ranked).
- Crafting
  - Fixed an issue with craft refund not sending the refund properly.

## 0.24.15101 Hotfix #1

`2025-10-31 17:00 UTC`

### Change

- Gameplay
  - A win by destroying 10 pumpkins in the Halloween game mode now gives max Trisel gain instead of opponent health percent.

## 0.24.15101 Patch

`2025-10-31 12:00 UTC`

### Changes

- Gameplay
  - We removed the ability to pre-select Blast abilities when it's not your turn to avoid issues.

### Fixes

- Gameplay
  - Fixed an issue with cards going invisible after a reconnection.
  - Fixed an issue with Exclusive card gained from the event not being acknowledged properly.
- Deck edition
  - Fixed an issue with deck edition not showing the correct runes on cards.
- Inventory
  - Fixed an issue with frozen boosters not showing a confirmation window before opening.

## 0.24.15087 Hotfix #2

`2025-10-31 08:00 UTC`

### Fixes

- Mission
  - The daily mission to win a duel is now validated in ranked and event duels.
- Gameplay
  - Fixed an issue with Draw of Fate level 3 not launching if played too fast.

## 0.24.15087 Hotfix #1

`2025-10-29 19:00 UTC`

### Fixes

- Gameplay
  - Fixed an issue with Draw of Fate level 1 using 100 Energy instead of 125.
  - Fixed an issue with Drone Command level 3 sending the card back to the controller instead of the owner.

## 0.24.15087 Patch

`2025-10-29 08:00 UTC`

### Changes

- Halloween event
  - Halloween is back in Blast!
  - The event will last until `2025-11-19 08:00 UTC`
  - This event brings a whole new gamemode specific to this event: 
    - Cursed Roots appear on the board. They do not grow on empty spaces, but are destroyed if the card they cover is damaged.
    - If they are not damaged in time, they turn into destructive pumpkins on the next turn!
    - Pumpkins block spaces but can be moved or destroyed.
    - When they explode, they inflict -200 power to adjacent cards.
  - When winning event duels, you have a 50% chance to drop a Garth Exclusive card. It has a 80% chance to be standard and 20% chance to be alternative. They are static and have a chance to be auto minted depending on your Mint Pass (Red Mint Pass 0.005%, Green Mint Pass 0.010%, Blue Mint Pass 0.020%, Legacy Mint Pass 0.035%, Golden Mint Pass 0.050%, Golden Legacy Mint Pass 0.065%).
  - Win duels to unlock exclusive cosmetics only unlockable during this event.
  - All cosmetics are also available in the Shop. The cosmetics available in the shop are the same as the ones you get while playing. If you buy the pack and already have some of the cosmetics, the price is not reduced and you won't get the cosmetics you already had.
  - The special Halloween gamemode also gives Ark and Trisel at the same rate as a Gold rank player in ranked. It gives unlocker chests at the same rate as Ranked duels. It doesn't drop Exclusive Leaderboard cards.
- Economy
  - Eternal Multiplier will be taken into account starting `2025-11-12 08:00 UTC`. All details will come in a future patch notes.
  - The amount of EM you have will be shown on your profile at this date.
- Leaderboard
  - The Champions are now recalculated only once at daily reset: Champions can't be demoted even if a non-champion gets more points. At daily reset, the 100 players with the highest mmr get the Champion rank. Other players get their rank based on the number of points they have.
- Gameplay
  - We completely reworked the way we technically display cards to improve performance. Duels should feel way smoother, especially on older devices. We also limited fps to 30 on mobile devices to reduce overheating.
  - Added opponent information on the mulligan screen (starting player and the Blast used by both players).
  - Added a text info when the player reaches the maximum amount of cards in hand.
  - Added a visual cue to gravitational wave level 3.
  - Added a differentiated win type depending on win/lose (Defeat by lowest health).
  - Added missing escape shortcut to the Heptagram, log and blast info popups.
  - Added back the Mmr shield display at the end of a duel.
  - Added information in log files to help us diagnose gameplay issues.
  - After a disconnect or loss of focus, the app now instantly reconnects to avoid specific issues due to the delay of reconnection.
- Shop
  - The VIP level is now shown in the shop.
  - Added specific standard cards to the daily Ark shop. All players will see the same card.
  - Some articles have seen their price adjusted to account for the specific card arrival.
- Collection
  - Changed the order of preferred card displayed in the card collection to show grade S cards over foil cards.
  - On the shred duplicated screen, we added a "minimum amount of cards to keep" selector for players that want to keep more than 1 card of each.
  - Added Frozen and physical state to cards display and in filters. Shred, craft and merge is disabled for frozen and physical cards.
  - Applied the new card stack style to all card stack screens (shred, deck edition, card selection to merge)
- Awakening
  - Added a popup when trying to craft a card while it's still pending mint to prevent issues.
  - Added a refresh of the header after an awakening so currencies are up to date.
- Openning
  - Added a recap of new cards at the end of an opening.
  - Added the ability to have a full view of a card in the card opening recap by clicking on it.
  - Added a confirmation popup before opening a minted chest or booster.
  - Added the rune to the grade S card preview.
- Dashboard
  - Added back the maintenance alert information.
- Authentification
  - Changed the cards displayed while downloading assets to season 4 cards.
- Reward screen
  - Ordered the rewards to show in order of priority: boosters, cards, cosmetics, currencies.

### Fixes

- Gameplay
  - Improved the display of the Heroes's Legacy end of turn attack display when it's the opponent's turn.
  - Fixed a display issue with the avatar overlapping the log screen.
  - Fixed some unlocalized text on the duel end screen.
  - Fixed a display issue with cards that could go "invisible" by moving under the board.
  - Fixed an issue with the opponent ui that could sometimes overlap the board on specific screen size.
- Shop
  - Fixed some unlocalized text.
  - Added missing escape shortcut to the redeem code popup.
- Collection
  - Fixed a display issue after claiming a collection mission progress, not refreshing properly after claiming missions containing cards as reward.
  - Fixed some display issues with rarity filters. Players can now better see when a rarity is selected.
  - Fixed an issue with the Header not showing the right amount of currencies with asian localizations (shortening characters missing).
  - Fixed a display issue with the prestige collection title.
  - Fixed an issue with the filter's escape shortcut not closing the filters properly.
  - Fixed a display issue with the collection icon shown in the top left.
- Merge
  - Fixed a display issue on the screen to select another card, showing a Hanzo placeholder everytime.
- Deck edition
  - Fixed an issue with the import, export and delete popup's escape shortcut closing the deck edit completely.
  - Fixed an issue with the heptagram popup escape shortcut closing the card deck edit.
  - Fixed an issue with the card back popup escape shortcut not showing back the back button.
  - Fixed an issue with the filter's escape shortcut not closing the filters properly.
- Reward screen
  - Fixed a display issue with the state bubbles not counting properly with many rewards.
- Dashboard
  - Fixed some unlocalized text.
  - Fixed an issue with the Ark display in the header missing a tooltip.
  - Added missing escape shortcut to deck selection popups.
- Missions
  - Added a loading while claiming a reward.
  - Fixed an issue with the mission count not counting properly to unlock the daily booster.
  - Fixed an issue with the craft mission not counting properly while crafting Eternal cards sometimes.
- Lobby
  - Added missing escape shortcut to settings and spectators popup.
  - Fixed some unlocalized text.
- Settings
  - Fixed an with profile id information overlapping on specific screen size.
- Inbox
  - Fixed some unlocalized text.
  - Fixed an issue with the "no message" information not showing up properly.
  - Fixed a display with the reward displayed when opening an already claimed message.
  - Added a loading when claiming rewards.
- Profile
  - Added some padding at the bottom of personalization screens so cosmetics from the last line are shown entirely.
  - Fixed a display issue with collections' card count.
- Authentification
  - Fixed a display issue with the downloading screen sometimes not showing the lore of the currently displayed card.
  - Fixed some unlocalized text.
  - Fixed an issue with the CGU screen checkbox having a smaller hitbox than intended.

## 0.24.14788 Hotfix #2

`2025-10-22 13:00 UTC`

### Changes

- Leaderboard
  - Now that qualifying is over, the leaderboard is now back to 100 players.

### Fixes

- Gameplay
  - Fixed a display issue with Drone Command level 3 sending the card back in the hand with affinities (the card didn't really had any affinities and was recalculated after endturn).

## 0.24.14788 Hotfix #1

`2025-10-17 13:00 UTC`

### Fixes

- Gameplay
  - Fixed an issue with Fireball 3 not being usable on some rare instances.

## 0.24.14788 Patch

`2025-10-16 09:00 UTC`

### Fixes

- Gameplay
  - Fixed a display issue with affinities on cards pushed with gravitational wave.
  - Fixed an issue in the custom lobby where energy was gained before turn 3.
- Shop
  - The shop is back on mobile devices! You can now purchase item in real money on Android and iOS.
- Mission
  - Fixed an issue with the missions validated count that would sometimes not allow you to claim the booster even if you finished all missions.

## 0.24.14777 Hotfix #1

`2025-10-14 09:00 UTC`

### Fixes

- Gameplay
  - Fixed an issue with affinities not being correctly deleted after a card has been destroyed by reaching 0 power.

## 0.24.14777 Patch

`2025-10-10 15:00 UTC`

### Changes

- Gameplay
  - Nerf
    - Draw of Fate level 1 costs increased to 125 Energy (up from 100). (Hotfix already live)
    - Gravitational Wave level 1 damage reduced to 50 (down from 100). (Hotfix already live)
- Opening
  - Added a hint when opening a booster.

### Fixes

- Dashboard
  - Fixed an issue with success notification on Dashboard not clearing after claiming and coming back to the dashboard.
- Inventory
  - Fixed an issue that allowed displays to be selected for bulk opening, even though only one display can be opened at a time.
  - Fixed an issue with inventory refresh after opening the last occurence of an item.
- Multi-lock
  - Fixed an issue with multi-lock preventing cards from being unlocked.
- Deck edit
  - Fixed an issue with rune statistics duplicating the display in some cases.
- Success
  - Fixed an issue with success filters not working.
- Card details
  - Fixed an issue with the "See on Marketplace" shortcut in card details of Eternal cards.

## 0.24.14751 Patch

`2025-10-09 16:00 UTC`

### Changes

- Gameplay
  - Added a rune tab to the heptagram to have a description of all rune effects.
- Success
  - Added the success panel in the profile. Previously called General missions, it is now located in the profile.
  - Each success gives Ark and success points. Success points track how much a player has been active and played the game.

### Fixes

- Gameplay
  - Fixed a display issue with the HL end of turn attack.
- Collection
  - Fixed an issue with product details refresh after a new craft
- Inventory
  - Fixed an issue with inventory refresh after opening the last occurence of an item.

## 0.24.14734 Patch

`2025-10-07 12:00 UTC`

### Changes

- Gameplay
  - Added a rune tab in the heptagram in game to show all rune effects.
  - Added precision to the level of Blast used in card details.
  - Added hints to rune play describing what the rune effect is when selecting a card.
  - Prevent the player from using Hack Blasts when the opponent doesn't have any card in hand.
- Collection
  - Added a rune panel in the statistics tab of the deck edit to display how many Runes of each type you have.
- Leaderboard
  - We changed the display of your points in your rank to be consistent with the current Champion display.
  - Players don't reset at 0 points when you get to a new rank anymore. Instead, you continue to increase your points throughout your rank advancement.
  - This is only a display change with your ranking points and doesn't change anything to the ranking system.
  - The display change is already live, but the amount of points needed to rank up will only updated with the 14716 version of the client.
  - Summary of rank thresholds:
    - Bronze: 0-1149 pts
    - Silver: 1150-1499 pts
    - Gold: 1500-1849 pts
    - Platinum: 1850-2199 pts
    - Diamond: 2200 pts+
- Card details
  - Added the date of when the numbering will be attributed to eternal cards’ card detail.
- Settings
  - Added client version and account id to the settings window.

### Fixes

- Dashboard
  - Fixed an issue with the deck selection, sometimes not registering a deck change.
- Gameplay
  - Fixed a display issue with affinities.
  - Fixed an issue with fields not applying their bonus to cards drawn after. (Hotfix already live)
  - Added precision to Overpowering rune's description. (Hotfix already live)
  - Added precision to Draw of Fate level 3's description. (Hotfix already live)
  - Fixed an inconsistency in Fireball level 3's description. (Hotfix already live)
  - Fixed a display issue with the HL end of turn attack.
  - Fixed a display issue when discarding showing power directly instead of a preview.
- Dashboard
  - Fixed an issue with the shop notification not showing until players go to the shop.
- Leaderboard
  - Fixed some display issues on the Leaderboard. Also added back the information panel.
  - Fixed a display issue with the leaderboard information popup.
- Custom lobby
  - Fixed an issue when leaving and rejoining a custom lobby preventing the start of the duel.
- Inventory
  - Fixed an issue with cards and boosters not being acknowledged properly when opening multiple boosters at a time and ending in the mailbox. (Hotfix already live)
- Mission
  - Fixed a display issue preventing users with specific screen size from collecting their daily booster.
  - Fixed an issue preventing the mission screen from closing. 
  - Fixed an issue with missions not completing when the duel started before the daily reset, and finishing after daily reset. (Hotfix already live)
- Merge
  - Fixed some display issues on the Merge screen.
- Profile
  - Fixed an issue with duel history sometimes showing incorrect avatar and avatar frame. (Hotfix already live)

## 0.24.14675 Hotfix #1

`2025-10-01 14:00 UTC`

### Fixes

- Gameplay
  - Fixed an issue with Overpowering not applying it's bonus correctly.
  - Fixed an issue with Draw of Fate level 3 burn and retry not working properly.

## 0.24.14675 Patch

`2025-10-01 08:00 UTC`

### Changes

- Season 4's first event: Heroes' Legacy qualifyings!
  - A new event is available starting at `2025-10-01 08am UTC`.
  - The purpose of this event is to determine our 8 finalists for Heroes' Legacy.
  - During this event, you will have to fight in a fresh era to determine the 8 best players until `2025-10-22 08am UTC`.
  - Win duels to unlock exclusive cosmetics only unlockable during this event.
  - All cosmetics are also available in the Shop. The cosmetics available in the shop are the same as the ones you get while playing. If you buy the pack and already have some of the cosmetics, the price is not reduced and you won't get the cosmetics you already had.
  - More info on the qualifying in this article: [https://www.crosstheages.com/fr-fr/news/cta/hl2025/](https://www.crosstheages.com/fr-fr/news/cta/hl2025/)
- Gameplay
  - We made some balance changes to some runes and Blasts that were outperforming or underwhelming:
    - Buffs
      - Overpowering Rune (Mantris) now allows you to empower another card on the board instead of in your hand.
        - Full description: Gives +25/50/100 power to a card on the board.
      - Draw of Fate level 2 costs 100 Energy (down from 150).
    - Nerfs
      - Abundance Rune (Dawn of War) now gives Draw Charges. When you have 2 draw charges, you automatically draw 1 card. This allows us to reduce the number of cards drawn with the rune and balance the drawing mechanic more easily.
        - Full description: Gain 1/2/3 draw charge(s). Accumulate 2 draw charges to draw a card.
      - Drone Command level 2 now has 2 charges (down from 3).
      - Fireball level 1 costs 75 Energy (up from 50).
      - Gravitational Wave level 1 costs 100 Energy (up from 75).
      - Hack level 3 costs 350 Energy (up from 300).
  - Reduced the time to play a turn to 75 seconds (down from 90).
- Mint
  - Removed the level 10 restriction to mint cards.

### Fixes

- Gameplay
  - Fixed an issue with Hack level 3, the stolen card didn't activate the rune.
  - Fixed an issue with Draw of Fate level 3 burn and retry part not working properly.
  - Fixed a display issue on mobile devices, the rune name could be shown behind the opponent's UI.
  - Fixed an issue with Hack level 1, 2 and 3 only showing the first 6 cards of the opponent.
  - Fixed an issue with the cards count after a mulligan.
- Opening
  - Fixed an issue with the 5 cards displayed not always showing the rarest cards. Also, when possible, the game tries to show different cards from the same rarity.
- Collection
  - Fixed an issue where Flex cards were still visible in-game. (hotfix already live)
  - Fixed an issue with some cards not showing their rune properly (H&H SR cards, unique and divine cards).
  - Fixed an issue with cards not disappearing from a player's collection after being traded.
  - Product details, when a parallax skin is activated on a card, the cards from the power list can incorrectly be turned.
  - Product detail, closing the card displayed in full art shows the catchline over the UI.
  - Card details, fixed the see on Marketplace redirection.
  - Card details, correctly show the Shred button on exclusive cards.
- Awakening
  - Fixed an issue with the bonus Exclusive card not displaying properly when won and the card was sent to the inbox.
- Merge
  - Fixed some redirection issues with the Merge menu.
- Inbox
  - Fixed a display issue on claimed currencies, not showing the proper icon.
  - Fixed an issue preventing you from opening mails once they have been claimed.
- Profile
  - Fixed a display issue on private profiles not hiding personalisation icons.

## 0.24.14618 Hotfix #2

`2025-09-29 08:00 UTC`

### Fixes

- Shop
  - Fixed an issue with payment processing not giving the item purchased in the shop. All purchased items are being reprocessed and should arrive in your in game mailbox.

## 0.24.14618 Hotfix #1

`2025-09-25 08:00 UTC`

### Fixes

- Gameplay
  - Fixed an issue with Mage, Overpowering and Explosive Level 2 and 3 damage calculation.
  - Fixed an issue with the Blast panel not allowing Blast usage after a discard that gives enough Energy to play a Blast.

## 0.24.14618 Patch

`2025-09-25 14:00 UTC`

### Changes

- Season 4!
  - Season 4: Dawn of War is here!
  - This season comes with new cards and their new border design. Every new card also has exclusive lore for you to discover.
  - This new season also brings a whole new gameplay, with more dynamic effects.
  - The whole app has received a new style with improved UX experience, notably: the Product and card details, the opening, the shop.
  - The last big improvement are the improved rewards, through the new unlocker system, daily missions, and shop content.
  - Let's dive in!
- Cards
  - All Cards have received a new improved border, integrating card name, artist and complete numbering. It allows us to only keep important information when dueling.
- Gameplay
  - The point system has been replaced with a health system. Both players start with 25,000 Health points. The goal is to reduce the opponent's health to 0.
  - Players inflict damage to the opponent at the end of their turn up to the sum of the power of the cards you control.
  - Special Abilities are replaced by Blasts. Blasts are abilities attached to a deck. Each collection has 3 Blast divided into 3 levels. You will have to select a Blast of each level to play a deck. You can only play one Blast of each level per turn.
  - Each level of Blast has different effects, different energy costs, different max uses. After a Blast is played, there is no capture retry if cards are moved.
  - We added an Energy system for playing cards and Blasts. You start with 650 energy and regain 500 energy at the start of each turn starting at turn 3. The cost to play a card is equal to its power. You can't have more than 1200 Energy at any time. The surplus is lost.
  - You can play several cards per turn as long as you have enough energy.
  - You can discard cards to regain energy. The first discard each turn gives you 25 Energy, the second gives 75 and every discard after gives 150.
  - You can have as many field cards as you like in your deck. Field cards don't cost energy to play. Field cards last for 3 turns and empower its element by the amount of power of the card. Only one field can be active at a time.
  - We removed the Trinity system. (But affinity remains).
  - We removed the double advantage/disadvantage in the heptagram. Now an element is only strong against 1 other and weak against another. Also changed the order of the Heptagram to keep it logical.
  - Captures are only made with a chain of 1.
  - If a card on the board drops to 0 power or less, it is destroyed.
  - You can have a maximum of 10 cards in your hand at any time. If you draw an 11th card, it is destroyed.
  - Players have 90 seconds to play their turn. If you don't play during your turn, your turn ends automatically. For your next turn you will have only 450 seconds to play your turn. If you don't play during your turn, your turn ends automatically. For your next turn you will have only 45 seconds to play your turn. If you don't play during that turn, you lose the duel. Playing something during a turn with reduced time puts back your turn duration at 90 seconds.
  - Win conditions are: 
    - Reduce opponent's health to 0,
    - The opponent doesn't have a card in his deck and has to draw,
    - The board is filled and player has more health than the opponent,
    - The opponent didn't play within the allowed time 3 times in a row.
  - First card immunity
    - To protect the first card played from being captured, we added an immunity to captures for the first card played during 1 turn. The card is not immune to Blasts usage.
  - Blasts
    - Fireball, tied to Heritage Arkhante set
      - Level 1 (50 energy): Permanently weakens a card by -200 power.
      - Level 2 (100 energy, 3 charges): Permanently weakens a card by -200 power. Opponent's cards on adjacent squares each lose -100 power permanently.
      - Level 3 (200 energy, 1 charge): Destroys a card. All other opponent's cards on the board lose -200 power permanently.
    - Drone Command, tied to Heritage Mantris set
      - Level 1 (75 energy): Allows you to move a card on the board to a different occupied location. The two cards swap positions.
      - Level 2 (200 energy, 3 charges): Allows you to move a card on the board to a different free location.
      - Level 3 (250 energy, 1 charge): Allows you to move a card on the board to a different occupied location. The card occupying that location is then returned to its owner's hand. If the owner's hand is full, the card is destroyed.
    - Hack, tied to Watch Dogs set
      - Level 1 (25 energy): You can view your opponent's hand.
      - Level 2 (150 energy, 2 charges): You can view your opponent's hand and destroy one card from their hand.
      - Level 3 (300 energy, 1 charge): You can view your opponent's hand and steal a card from their hand to place it directly on the board.
    - Gravitational Wave, tied to Heritage Rift set
      - Level 1 (75 energy): Unleashes a wave of energy on a row or column which pushes the first card encountered in that direction one cell. If the card cannot be moved, it loses -100 power.
      - Level 2 (100 energy, 3 charges): Throw an energy ball onto a cell on the board, which pushes all adjacent cards outwards by one cell. If a card cannot be moved, it loses -100 power.
      - Level 3 (250 energy, 1 charge): Launch a wave from the edge of the board to move all the cards on the board by one cell. If a card cannot be moved, it is destroyed.
    - Draw of Fate, tied to Dawn of War set
      - Level 1 (100 energy): Draw 1 card without triggering overdraw.
      - Level 2 (150 energy, 3 charges): Look at the top 3 cards of your deck, then reorder them.
      - Level 3 (200 energy, 1 charge): Choose an element and draw 1 card. If the card matches the chosen element, you may play it for free on the board or burn it to repeat this action once. If not, you don't lose any charge and add the card to your hand without triggering the over-draw.
  - Runes
    - Runes introduce unique passive effects tied to collections, activated upon placement or while the card remains in play. These automatic effects are exclusive to S-grade cards (Static or Eternal) and are tied to the card’s collection (e.g., Isalys will always be Explosive 1, while Solis S will always be Mage 1). Each rune in the game (1 effect per collection) exists in 3 levels.
    - Combo Rules: Effects combine based on the following rules:
      - Each S alternate card: Level 1 effect of its collection.
      - An S combo made with two alternates of the same collection: Level 2 effect.
      - An S combo made with different collections: Level 1 effect for each collection.
      - An S combo made with three alternates of the same collection: Level 3 effect.
   - Mage - Heritage Arkhante set
      - Level 1 : Deal 25 damage to another card of your choice.
      - Level 2 : Deal 50 damage to another card of your choice.
      - Level 3 : Deal 100 damage to another card of your choice.
    - Overpowering - Heritage Mantris set
      - Level 1 : Gives +25 power to a card in your hand.
      - Level 2 : Gives +50 power to a card in your hand.
      - Level 3 : Gives +100 power to a card in your hand.
    - Concord - Watch Dogs set
      - Level 1 : The affinities on this card grant +50 additional power.
      - Level 2 : The affinities on this card grant +100 additional power.
      - Level 3 : The affinities on this card grant +150 additional power.
    - Explosive - Heritage Rift
      - Level 1 : Deal 25 damage to each adjacent enemy card.
      - Level 2 : Deal 50 damage to each adjacent enemy card.
      - Level 3 : Deal 100 damage to each adjacent enemy card.
    - Abundance - Dawn of War
      - Level 1 : Draw 1 card.
      - Level 2 : Draw 2 cards.
      - Level 3 : Draw 3 cards.
  - To sum up actions order when playing a card, they are played in this order:
    - Card Played
      - Rune activation,
      - Card suppression if power at 0 or less,
      - Friendly affinity,
      - Card capture,
      - Remaining affinities.
 - New capture indicator
    - Rune effects are applied before calculating captures.
    - A new improved capture indicator is put on cards that need an action such as a Mage rune usage to be captured.
- Ranked
  - The first week of this season is considered the pre-season.
  - A new ranked era will begin October 1st for 3 weeks that will also be the qualifier for the Heroes's Legacy finals. Read more in this article: https://crosstheages.com/en-us/news/cta/dawn-of-war-heroes-legacy/
  - The Gladiator ranks have been removed and the Champion rank now has 100 places. Once per day the Top 100 players at diamond ranks will be classified as Champions, and won't be able to demote from Champion until the next reset.
  - To encourage fighting at higher ranks, a decay will be applied to players of the Champion rank that didn't play at least a game this day.
  - During the launch event, you will benefit from boosted Trisel gains in Ranked duels.
- Season 4 boosters
  - Same as season 3, there are 4 tiers of boosters and displays available in the Shop. All boosters contain static cards.
  - Tier 1 booster contains 5 static cards from the Dawn of War set for $0.99.
  - Tier 2 display contains 12 boosters of 5 static cards (60 cards) from the Dawn of War set for $9.99.
  - Tier 3 display contains 24 boosters of 5 static cards (120 cards) from the Dawn of War set for $18.99. This display contains 1 Bonus Exclusive Standard card from: Tsanah Krey, Sveri, Lyle.
  - Tier 4 display contains 48 boosters of 5 static cards (240 cards) from the Dawn of War set for $34.99. This Display contains 1 Bonus Exclusive Alternative card from: Tsanah Krey, Sveri, Lyle.
  - Every booster also contains 1 Heritage card that is a random card from the 3 Heritage sets (Heritage Arkhante, Heritage Mantris, Heritage Rift). Cards are standard rank 1.
  - Every booster also has a 2% chance to contain a random Exclusive standard or Alternative card from: Tsanah Krey, Sveri, Lyle.
  - Season 4 minted cards will benefit from a numbering pool lasting until the end of season 4. All numberings will be decided when the season ends.
- Season 4 Exclusive cards
  - Tsanah Krey, Sveri, Lyle can be acquired by buying and opening shop packs.
  - Hadrien Lys'Ortens and Malek Tornhil can be gained by winning ranked duels. They are static and have a chance to be auto minted depending on your Mint Pass if you are Platinum rank or higher (Red Mint Pass 1%, Green Mint Pass 2%, Blue Mint Pass 4%, Legacy Mint Pass 7%, Golden Mint Pass 10%, Golden Legacy Mint Pass 13%).
  - Crested Akka can be earned randomly when Awakening of Merging cards. When crafting Static cards, the Exclusive card is static and when crafting Eternal cards, the Exclusive card is Eternal.
- Super-combo!
  - Maa, the super combo card has been released!
  - You can craft it by merging Arkhel, Riona and Sijin.
- Missions
  - Daily missions have been simplified to include more aspects of the game and faster completion as well as new improved rewards.
  - Weekly missions have been removed.
  - General Missions have been renamed to Success, and are now accessible in the profile.
  - Some old General Missions concerning the old gameplay have been deleted. If you had it completed but not claimed, we claimed that for you and sent you the rewards by mail.
- Unlockers
  - Unlockers are now directly accessible on the Dashboard.
  - You gain an unlocker pack every time you win a duel if you have a free unlocker space.
  - There are 4 tiers of unlocker boosters. Higher tiers give more cards, better odds, but take more time to unlock.
  - There is no more unlocker stock. If your 4 slots are full, you can't gain an unlocker chest anymore until a slot is free.
- Shop content
  - All shop content have been revamped and you will be able to find:
    - Seasonal boosters: contains static packs of the current season.
    - Static Stones and Ark: contains packs of Static Stones and Ark, Trisel to Ark conversion and Eternal Stone to Static Stone conversion, and free daily Ark and Static Stones.
    - Random daily in Ark: Every day, 3 random items are available for everyone in the shop. It can contain static stones, boosters, cards and cosmetics. 
    - Daily boosters in Ark: Every day, you can purchase up to 3 boosters of the current season in Ark.
    - Limited offers: The first time you gain a card that is used in a combo, a pack will be available for 2 days containing the other card and the necessary Ark and Static stones to craft the Combo card.
    - Promotional packs: Packs in limited quantities containing enough Ark and Stones to craft a combo card.
- Flex cards
  - To account for the mint delay, Flex cards from season 3 will be transformed into static cards on October 22nd.
  - The Flex status of cards will be removed. All season 4 static cards can now be minted.
  - Chests and Boosters are no longer able to be minted.
- Profile
  - We added some skins for in-game end-turn attack and Blast bar. You can win those during events and purchase them in the shop.
  - You can now set up to 8 emotes to play in-game.
  - We removed Profile banners and in-game Footer as they were not satisfying enough for us. All purchased items have been reimbursed for 1500 Trisel per cosmetic.
- UX improvement 
  - The product detail has seen a complete overhaul, allowing for easier access to where the card can be acquired, the powers accessible to that can, what card it can craft, it's Lore, and other versions of that card (Exclusives, Uniques and Divines)
  - We added 2 deck slots to everyone. You now start at 6 slots and can get up to 10 deck slots at level 20.
  - We revamped the duel end screen to show information more clearly.
  - We added a PC shortcut with the Escape key to close an opened popup.
- Miscellaneous
  - All static chests from season 1, 2 and 3 have been opened.
