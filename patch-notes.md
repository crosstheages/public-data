# Cross The Ages: TCG Early Access Patch Notes

## Direct Links

- 0.23
  - [0.23.12334](#02312334-patch)
  - [0.23.12311 Server-Update #1](#02312311-serverupdate-1)
  - [0.23.12311 Hotfix #1](#02312311-hotfix-1)
  - [0.23.12311](#02312311-patch)
  - [0.23.12301](#02312301-patch)
  - [0.23.12203](#02312203-patch)
  - [0.23.12188](#02312188-patch)
  - [0.23.11981](#02311981-patch)
  - [0.23.11821](#02311821-patch)
  - [0.23.11818](#02311818-patch)
  - [0.23.11731 Hotfix #1](#02311731-hotfix-1)
  - [0.23.11731](#02311731-patch)
  - [0.23.11709](#02311709-patch)
  - [0.23.11379 Hotfix #1](#02311379-hotfix-1)
  - [0.23.11379](#02311379-patch)
  - [0.23.11351](#02311351-patch)
  - [0.23.11302](#02311302-patch)
  - [0.23.11252](#02311252-patch)
  - [0.23.11206](#02311206-patch)

## 0.23.12334 Patch

`2025-06-02 14:00 UTC`

### Changes

- Shop
  - With the end of the Jün Exclusive rotation in the shop, starting `2025-06-04 8 am UTC` and until the end of season 3, the bonus Exclusive card available in the shop for a purchase of a 24 or 48 packs box will be random from the 5 cards already released.
    - The 24 packs box will contain one of the following cards : Gravowl, Ailene, Tannila, Orchid or Jün Standard Exclusive card. The odds for each card is 20%. Rank odds remain 20% for each rank. Foil odds remain 10%.
    - The 48 packs box will contain one of the following cards : Gravowl, Ailene, Tannila, Orchid or Jün Alternative Exclusive card. The odds for each card is 20%. Grade odds remain C:70%, B:22%, A:7%, S:1%. Foil odds remain 10%.
  - The update is currently rolling on all platforms and the new version will be mandatory to play at `2025-06-04 8 am UTC`.

## 0.23.12311 Server-Update #1

`2025-04-30 08:00 UTC`

### Changes

- End of 2 years Anniversary event

## 0.23.12311 Hotfix #1

`2025-04-07 13:00 UTC`

### Fixes

- System
  - We made significant changes to the way we handle duels processed by the servers. The initial deployment was planned to be alongside the new gameplay but with the influx of players coming for the event, some issues resurfaced and we made the decision to take some time to deploy some of the changes beforehand. 
  - You should see way less crashes than before, but may still encounter some. The new structure also allows us to automatically restart the processing unit when a crash occurs. It means that even if a crash occurs, your game should go back to normal within a minute progressively. Successive games should also be faster to try and catch up the lost time.
  - Deploying big architecture changes is hard to test at a large scale and we may encounter unplanned issues. We think this is the best time to make those changes at the wake of the new gameplay changes.

## 0.23.12311 Patch

`2025-03-27 16:00 UTC`

### Fixes

- Play
  - Fixed a display issue with the duel end screen not showing the Blockchain State of the Exclusive card awarded.
  - Fixed a display issue with the Exclusive cards won in duels not being properly acknowledged and being distributed through the inbox.
  - Fixed a display issue with the Reverse SA animation being smaller than intended.
  - Fixed the french localization of Chaka's event avatar.
- Inventory
  - Fixed an issue with the opening animation showing missing assets.

## 0.23.12301 Patch

`2025-03-16 08:00 UTC`

### Changes

- Please note that this is the last update that will be distributed through our launcher. All subsequent updates will only be distributed through Epic Games, Apple Store and Google Play Store.
- 2 years Anniversary event
  - To celebrate the TCG's 2nd birthday, we're running a special event until April 29, where you can win exclusive cosmetics and cards.
  - Gain an exclusive Avatar, Card back, Profile Banner and 2 emotes by winning Raids. When winning a Raid, you are randomly rewarded with one of the cosmetics that you don't have yet.
  - Gain 5 different exclusive cards by winning ranked duels and Raids: Muders, Gryffin and their combo! 
    - In Raids: 
      - The chance to get a card varies depending on the difficulty of the Raid and your ranking in the damage leaderboard for this boss.
      - You can win standard cards in T1 raids, Alternative cards in T2 raids and the combo in T3 raids. The ranks, grades and foil status are random following the usual rates. (Rank: 1:20%, 2:20%, 3:20%, 4:20%, 5:20%; Grade: C:70%, B:22%, A:7%, S:1%; Foil 10% )
      - Those cards have a 67% chance to be Static and 33% chance to be Flex. 
    - In ranked duels:
      - When you win a duel, you have a 50% chance to drop an Exclusive card. 
      - You can only get 1 card per duel and the advancement, rank, grade and foil status is random following the usual rates. (Advancement: Std: 80%, Alt: 15%, Cmb: 5%; Rank: 1:20%, 2:20%, 3:20%, 4:20%, 5:20%; Grade: C:70%, B:22%, A:7%, S:1%; Foil 10% )
      - The chance for this card to be Flex depends on the VIP level you are (0.23% at VIP 1, 0.75% at VIP 2, 1.88% at VIP 3, 3.75% at VIP 4, 7.5% at VIP 5, 18.75% at VIP 6, 37.5% at VIP 7, 75% at VIP 8).
  - The Reverse Special Ability returns for the duration of the event, given to everyone at the start of the event.
    - Full description: When played, your Leader reverses the conditions for capturing a card for 3 turns: if you were to capture a card, it is not captured, and vice versa.
- Card skins
  - We released parallax skins for all cards from season 1, season 2 and watch dogs sets.
  - We also improved the Foil effect on all parallax skins.
  - We added the last missing level 2 and 3 animations for Exclusive and Special Rare cards.
- Collection
  - Added the ability to filter more precisely when selecting cards to shred.
  - Added the ability to lock/unlock multiple cards at once.
- Shop
  - The next exclusive card will be available in the shop on `2025-04-09 8 am UTC` and until `2025-06-04 8 am UTC`.
- Notification
  - Added a notification when the unlocker booster stock is empty for vip lv 2 and more.

## 0.23.12203 Patch

`2025-02-19 18:00 UTC`

### Fixes

- Play
  - Fixed an issue with fields sound persisting after the end of a duel.
  - Fixed mixing on different field sounds.
  - Fixed field color effect for some alternative fields.
- Collection
  - Fixed the crafting shortcut on SR cards in product details.
  - Fixed the display of the rank in the card stack.
  - Fixed card name search bar with some characters.
  - Fixed card unselection in the card selection shred after a long scroll.
  - Fixed the cards displayed in card details after a redirection from the Merge.
- Missions
  - Fixed some missions without text (already live).
- System
  - Fixed an issue that prevented the game from launching on older devices.
  - Fixed a notification system issue that sent the same notification to the same device several times (already live).

## 0.23.12188 Patch

`2025-02-12 08:00 UTC`

### Changes

- Push notifications
  - Add push notifications for phones in several cases:
    - When a pack is completed in the unlocker.
    - When an unlocker slot is available and a pack is available.
    - When the start of a raid's fight phase is 15 minutes away and the player is not registered.
    - When a raid's fight phase has begun and the player is registered.
  - An option is available to disable push notifications. On some phones, you may have to manually enable push notification through the Operating system.
  - Notifications are still in an early stage and players could encounter some issues on specific devices. We will monitor this closely and make adjustments if necessary.
- Missions
  - As a first step to refactor our code base, we have deleted some daily, weekly and general missions linked to elements. If you had unclaimed General Missions, we claimed them automatically and sent you the rewards.
- Collection
  - Added numerous missing level 2 and 3 animations for Exclusive and Special Rare cards.
  - When entering the merge screen from an alternative card: this card is automatically pre-selected.
  - When entering the merge screen from the collection while filtered on eternal/static or foil/non foil, merge toggles are pre-selected on these parameters.
  - Using the select card shred from a prestige collection now only shows cards from the prestige collection.
  - If the collection is filtered on foil or non-foil, the toggle foil is no longer displayed in the card detail.
  - Added the toggle foil in card details even if the user doesn't own the card.
  - Changed the way the element filter works when selecting the first element.
- Profile
  - Return of the ability to select a card in the profile.
  - Added a card back tab to view the list of available card backs and how to obtain them.

### Fixes

- Collection
  - Corrected the card numbering in prestige card's card details.
  - Fixed inability to awaken from the global collection.
  - Correction of the faction and power filters from the global collection.
- Deck edition
  - Fixed a glitch with the heptagram button in deck edition on some rare occasions.
- Pack opening
  - Corrected the card back display when opening packs.
- Missions 
  - The reroll button is now grayed out if the player has already used his daily reroll.
- Play
  - Fixed an issue with the sound played when playing a field card playing multiple times.

## 0.23.11981 Patch

`2024-12-19 12:00 UTC`

### Changes

- Collection
  - Prestige sets now also show non-collected exclusive cards. (Hotfix already live)
  - Added a toggle on the set list to show the player cards from all combined collections.
  - Sets are now displayed from latest release to oldest release in the list of sets. We also added a button to clarify the switch between classic sets and prestige sets.
  - The cards from a set are now loaded dynamically when scrolling to avoid long load times.
  - On cards displayed in a card stack, we added two indicators for when the card is already in a deck and for when a card is locked.
  - Improved the appearance of the set mission window and added a link to the profile of the player to have a better overview of the collection progression.
  - Quick-filter icons for the card stack of alternative cards now change color depending on the rarity of the card.
  - Rarity filters now only show rarities available in that set.
  - On PC, the card name research now has focus directly after opening the filters to facilitate card search.
  - Changed the appearance of some of the filters to improve readability of what is selected or not.
  - When no cards are returned by the filters, we added a text where the cards would be to indicate that the search returned no result.
  - Filters are now reset when opening a card stack or by returning to the set list to avoid confusion with already selected filters.
  - When filtering cards in a set, the card details now also apply that filter when showing previous/next cards.
  - We added a setting in the filter Panel to show the power of the cards displayed.
- Crafting
  - Added a warning popup when trying to merge cards containing at least one grade S card.
  - Changed the icon and position of the information and grade percentage icons for the merge to make it more clear.
  - In the merge screen, we added a button in the card selection screen to craft another alternative card.
  - The merge toggles are now pre-selected depending on where you come from :
    - Coming from the awakening of a card, the toggles selected are now the ones from the previously awakened card.
    - Coming from the list of cards from a set, if you filtered with Eternal cards or Foil cards, the same toggles are selected in the merge screen.
- Deck edit
  - Added a small delay after adding a card to a deck to avoid mistakes when quickly tapping a card multiple times.
  - When selecting the Field quick-filter, deselect all other power filters.
- Shop
  - Added a timer on exclusive cards in the shop from the Rift series indicating the remaining time before the next Exclusive card.
- Bug report
  - Added a category selection when reporting issues directly to make it easier to track in internal tools.
- Cards
  - Some cards have seen their artist changed to indicate the Artist name directly instead of the Polar Engine Art Studio.
- Other
  - Changed all webview redirection to the new portal.
  - Added a skip button to the introduction video.
  - Changed the way we display currencies to shorten display length.

### Fixes

- Collection
  - Fixed an issue with the duplicate shred functionality sometimes not shredding all duplicates cards. (Hotfix already live)
  - Fixed a display issue with craft icons on the list of cards not refreshing properly after shredding the last card.
  - Fixed a display issue with the card details showing rarity borders on non possessed cards instead of greyed out borders.
  - Fixed a display issue with the card details showing incorrect faction icons for Rift and Mantris cards.
  - Fixed a display issue with the tooltip above decks in the deck list that would show outside of the screen for first and last decks of the list.
  - Fixed a display issue with the shred duplicates window missing faded background.
- Crafting
  - Fixed a responsive issue on the Burn window for specific devices.
  - Fixed a display issue with the power up and awakening window showing incorrect faction icons for Rift and Mantris cards.
- Deck edit
  - Fixed a display issue with the Heptagram being cropped on specific screen resolutions.
  - Fixed an issue with element filters sometimes acting incorrectly when deselecting the last filter.
- Opening
  - Fixed a display issue with opening animation for season 1 boosters showing a chest animation instead of a booster opening.
- Duel
  - Fixed a display issue with the Raid boss art on the end screen of a duel being cropped.

## 0.23.11821 Patch

`2024-11-28 15:00 UTC`

### Fixes

- Duel
  - Fixed a memory leak that could cause a crash after multiple duels. 

## 0.23.11818 Patch

`2024-11-27 10:00 UTC`

### Fixes

- Collection
  - Fixed an issue with the merge window not allowing the player to select the card with the grade they want.
  - Fixed a display issue with the awakening animation showing an invisible card if timed between two grade previews.
  - Fixed a display issue with the card name and title sometimes overlapping in the power up window.
  - Fixed a display issue with the card shown as a preview of the awakening showing an incorrect numbering.
  - Fixed a display issue with the card shown as a preview of the awakening still blinking even after canceling the awakening.
  - Fixed a display issue with the awakening not allowing to return to rank 5 when showing the preview for awakening.
  - Fixed a display issue with the icon of the faction of the card in the power up screen not changing according to the card faction.
  - Fixed a display issue with the card shown after an awakening to redirect to the merge window, sometimes appearing without the art.
  - Fixed an issue with cards not being acknowledged after receiving them from the forge and collection missions.
  - Removed the shred icon from the card stack shown when clicking the craft shortcut.
  - Fixed a display issue with the card stack showing incorrect progress bars for ranks in the cards display other than rank 1.
  - Fixed a display issue with the card stack showing incorrect style for the rank quick filter other than rank 1.
  - Fixed a display issue with the mint window not showing the same amount of CTA Token required to mint a card as the portal.
  - Fixed a display issue with the product detail sometimes showing left and right cards in full color even if the card was not owned.
  - Fixed a display issue with the product detail footer not refreshing properly after minting a card.
  - Fixed a display issue with the product detail showing the card on the left on the first card of a collection on large screens.
  - Fixed a display issue with the product detail showing incorrect faction icons for Mantris and Rift cards.
  - Fixed a display issue with the product detail responsiveness when swiping rapidly between multiple cards.
  - Fixed a display issue with the product detail unlocking the craft menu for flex cards by locking and unlocking them, resulting in errors.
  - Fixed an issue with the craft button in the product detail not directly redirecting to the awakening tab with the Alt button selected.
  - Fixed a display issue with cards not refreshing properly after buying a skin.
  - Fixed a display issue with card details not refreshing properly after shredding the card, allowing actions that would end up in errors.
  - Fixed a display issue with the lore tab in the product detail briefly showing placeholder text when loading.
  - Fixed a display issue with the lore tab in the product detail showing black borders on very large devices.
  - Fixed some delays after the swap left/right of a card before interacting with the new card.
- Shop
  - Fixed an issue with shop redirections not correctly scrolling to the right part of the shop.
  - Fixed an issue with the remaining time of the rift card collection showing inaccurate time.
- Inventory
  - Fixed an issue with the eternal shard combine not opening the burn popup.
- Raid
  - Fixed a display issue with the Raid Leaderboard not correctly centering cards in the banner.
  - Fixed a display issue with the duel end screen not always showing the boss art.
- Game mode selection
  - Fixed an issue with the deck selection not invalidating a deck that had been changed and was incomplete.
- Custom games
  - Fixed display issues after reconnecting to a custom lobby.
  - Removed the competitive custom lobby option as we don't need it anymore.
- Versus
  - Fixed a display issue with the Versus screen not properly centering Leaders art.

## 0.23.11731 Hotfix #1

`2024-11-19 12:00 UTC`

### Fixes

- Mint
  - Fixed an issue with the mint process sometimes taking longer than expected.

## 0.23.11731 Patch

`2024-11-15 14:00 UTC`

### Fixes

- Collection
  - Fixed an issue with the shred window not showing the burn window, preventing players to shred Eternal cards.
  - Fixed an issue with the burn window showing even on static cards if the player had a pending burn.
  - Fixed a display issue with the card stack showing incorrect progress bar for ranks in the cards display.
  - Fixed a display issue with the card stack showing incorrect style for the rank quick filter.
- Shop
  - Fixed an issue with payment with stripe. 
- Ranked
  - Fixed an issue with Ranked duels end screen relaunching duels automatically after stopping a Raids auto queue from the VIP Program. 

## 0.23.11709 Patch

`2024-11-13 08:00 UTC`

### Changes

- Crafting
  - Crafting is available now for all players!
  - A numbering pool will be in place until `2024-11-22 8 am UTC`.
  - Crafting is directly available in the card detail of a card. Either by selecting a specific card in the card stack and going to the craft tab, or directly in the Alternative or Combo card you want and clicking the Craft Button!
  - Awaken standard rank 1 cards in one click and Merge combo cards directly without the need to manually awaken all reagent cards! 
  - Powering up cards now doesn't require you to sacrifice cards, but instead uses stones and a currency.
  - Static cards can now be crafted and require Static Stones and Arks. Eternal cards require Eternal Stones and Trisel. Flex cards cannot be crafted directly anymore. They first have to be converted into Static or Eternal.
  - When crafting a combo card, odds now takes all reagent card's grade into account at pro rata.
    - ie: The odds for merging a grade C card and a grade B card will give you...
      - Before update: grade C 70%, grade B 22%, grade A 7%, grade S 1%.
      - After update: grade C 53.3%, grade B 34.3%, grade A 10.9%, grade S 1.5%.
- Collection
  - We added a new setting in the filters to show card rarity on the list of cards from a set. 
  - We reworked the quick filter display in the card stack so it is easier to see which one is selected or not. We also added a rank/grade quick filter and reworked the Foil filter with 3 states (foil and not foil / Only foil / No foil)
  - We added the cta token & free mint display in the header when converting a card in Eternal.
  - We added a "Select All" button in the Shred select card screen to select all currently filtered cards.
  - We added a quick filter option in the card stack to filter by rank or grade. The rank/grade is now displayed in the top left corner of the cards.
- VIP
  - Added a level 8 to the VIP System.
  - This level is available at 100 000 VIP points and unlocks
    - the possibility to queue raid automatically,
    - +1000 to the maximum energy,
    - a 100% progress to the Exclusive card.
- Shop
  - We improved the display for boosters in the shop.
- Dashboard
  - We added a notification of the shop icon when players still have the daily claim for Ark and Static Stones available.
- Cards
  - We renamed some cards so they better fit the lore of Cross the Ages. The change will be made progressively as we have to update all cards on the Blockchain.
    - Alvilid (Birth of Arkhante 132 & 133) into The Shores
    - Sea Dragon (Birth of Arkhante 72 & 73) into Sea Drak
  - All cards are now translated when changing the localization of the application. It is only translated in French for now but we plan on extending this to other languages.
- Event
  - Now that crafting is available, the Trisel bonus is now reduced to +25% until `2024-11-25 8 am UTC`
  - The end of the Mantris mint has been postponed to `2025-01-01`

### Fixes

- Deck Edition
  - We fixed a lot of issues related to deck building and the auto deck functionality
    - Added back the same card swap button on cards that are the same as a card already added, that swaps an already added card with the selected card but from a different power/display (exclusives).
    - Added a power warning directly in the deck edit screen to inform you when going above the 15000 power threshold.
    - Added an heptagram button when editing a deck.
    - Added toast notification after some actions to add feedback (duplicate deck, export deck, ...).
    - Simplified the auto deck functionality by removing the deck type choice as it was already made in previous steps.
    - Fixed the adventure auto deck sometimes creating 0 power decks.
    - Fixed many display and usage issues.
- Custom games
  - Fixed an issue with the custom game preparation screen closing lobby on mobile when switching windows.
- Card lore
  - We fixed a few display issues in the card lore section.
- Card detail
  - We fixed a display issue with the swipe on cards with a skin activated that could lead to transparent cards.

## 0.23.11379 Hotfix #1

`2024-10-23 12:00 UTC`

### Changes

- Special Ability Balancing
  - Field Influence: Fields are now empowered by +50 power (up from +40). This SA is now a passive effect and doesn't require the control of the Leader to be activated.
    - Full text: Empower your field cards by +50 power and weaken opponent's field cards by -30 power. This is a passive effect and applies at the start of the duel.
  - Power Stacking: The maximum power a Leader can be empowered is now 740 (up from 725).
    - Full text: At the start of your turn, as long as you keep your Leader in your hand, empower it accordingly if your card is a: Mythic/S = 20; Ultra rare/Special rare/A = 15; Rare/B = 10; Uncommon/Common/C = 5. The power of the Leader can not exceed 740.

## 0.23.11379 Patch

`2024-10-18 08:00 AM UTC`

### Changes

- Airdrop
  - On `2024-10-18 08:00 UTC`, every Honora & Hannibal owner will receive a new Rift SR card with the mirrored attributes from their H&H card.
- Filters
  - Changed the visual around a selected filter button to clarify when it has been selected.

### Fixes

- Shred
  - Fixed a display issue with the shred all still showing a preview of stones earned when no rarity or rank was selected.
- Collection
  - Fixed a display issue with the lore claim flag persisting on a card after a claim until the collection is closed and reopened.
  - Fixed a display issue when switching to the previous or following card rapidly.

## 0.23.11351 Patch

`2024-10-09 08:00 AM UTC`

### Changes

- Airdrop
  - This week marks the first airdrop of Rift SR if you are eligible: Phosphene! 
  - Along with the SR, we will also send the first Airdrop for the VIP Program advantage: Flex Rolls Airdrop for VIP level 6 and 7. The Ash Exclusive card Airdrop will start next week as players accumulate enough drop rate.
  - Added the weekly Flex Roll and the Exclusive card percent in the VIP program window.
- Collection
  - Improved the full art of a card to hide all other UI elements and show the Artist of each card.
  - Improved the skin page of each card to better show the displayed skin.

### Fixes

- Collection
  - Fixed an issue with the Foil toggle being displayed on unowned cards.
  - Fixed a display issue with the mission claim notification not disappearing after claiming a reward.
- Forge
  - Fixed an issue with the Flex Roll not being displayed in the Header.

## 0.23.11302 Patch

`2024-10-03 14:00 PM UTC`

### Changes

- Collection
  - Simplified the card detail and show directly the Footer instead of having to swipe from the bottom or click the arrow at the bottom.
  - Clarified the Read Lore functionality for the fact that players claim Ark by reading it and not spending it.
  - Added a Foil toggle on the product detail to switch between the Foil version of a card and its non-Foil version.
  - Limited the number of cards taken by the shred duplicate functionality to 10 000 cards at a time. If you want to shred more than that, you will have to shred duplicates multiple times. This is to alleviate server load when shredding cards. (Available with next server restart)

### Fixes

- General
  - Fixed an issue that caused connection losses after some time in the application.
- Ranked Leaderboard
  - Fixed a display issue with the Leaderboard not properly showing the Flex Roll drop rate.
  - Fixed a display issue at the end of a duel not showing when you won a Flex Roll. Players have been dropping Flex Roll but they were not shown. Champions ang Gladiators can check in the Forge if they received any.
- Collection
  - Fixed a display issue with the Read Lore functionality displaying text in FR instead of EN.
  - Fixed some white artifacts on some cards with parallax skin.
- Deck edit
  - Fixed an issue with the power filter not working properly.
  - Fixed an issue with SA Banner not correctly applying the deck cost reduction.

## 0.23.11252 Patch

`2024-09-27 08:00 PM UTC`

### Changes

- Collection
  - Added a notification on the collection mission button when there is rewards to claim
  - Added some loading animation after filter changes.
  - Added a progress bar on the loading of animation level skins.
  - After buying a skin for a card, it is now directly activated.
- Raids
  - Added more Rift cards to the Raid boss. (Hotfix already live)

### Fixes

- Collection
  - Fixed the Foil filter selection being inverted.
  - Fixed a display issue that showed Level 1 animation to Rift cards skins. (Hotfix already live)
  - Fixed an issue with the card stack not opening. (Hotfix already live)
  - Fixed an issue with the Shred value of SR cards Hannibal & Honora and Erika & Tiger Robot. (Available with next server restart)
- Deck Edit
  - Fixed an issue with the list of cards not showing all elements of combo cards and only showing one element. (Hotfix already live)
  - Fixed a display issue with the tooltip on the warning icon when editing a deck to explain the reason it's invalid.
- Forge
  - Fixed the subtitle being inverted between flex and static cards.
- Shop
  - Fixed an issue with the Exclusive card not appearing directly in the player collection and instead being sent to the inbox.
  - Fixed an issue with the Exclusive card power display. (Hotfix already live)
  - Fixed responsive issue in the convert stone and Ark window.
  - Moved the gift icon so it doesn't overlap the Element icon.
  - Fixed some missing localization.
- Dashboard
  - Fixed a display issue with the Energy refill timer.
- Inventory
  - Fixed a display issue with the opening of multiple packs showing the same cards.
- Adventure
  - Fixed the remaining time display for the weekly challenge.
- Raids
  - Fixed an issue where the raid boss could be a field. (Hotfix already live)
- System
  - Fixed an issue with the webview not being shown when clicking on a link.

## 0.23.11206 Patch

`2024-09-25 06:00 PM UTC`

### Changes

- Rift season
  - Season 3: Birth of Rift is here! You will be able to open your presale packs on `2024-09-26 06:00 PM UTC`. This season will feature up to 210 cards with 152 available right away.
  - Pack of Rift cards will be available in the shop on `2024-09-25 06:00 PM UTC` to give you some time to open your presale packs.
  - This season, you can also buy Ultra, Omega or Neo boxes that contain respectively 120, 240 and 480 Rift Cards. Those packs also come with an Exclusive card. The advancement, rank and grade of the card is random and determined the moment you buy a box. This Exclusive card will change every month. This month features Gravowl!
  - You will be able to mint these cards directly but the numbering for all Rift cards will not be determined until `2024-10-04 08:00 AM UTC`.
  - A whole new batch of missions have been added and all the missions will give Rift shards, cards or Packs. Unlocker, Arena duels and Adventure challenges now award Rift shard, cards or packs.
  - The Mantris series have been removed from the shop to make room for the Rift series! 
- New items
  - We added a new currency named Ark. Ark is exclusively a free to play currency. It is gained abundantly from playing the game everywhere, collecting cards, reading about their lore. It is used to craft Static cards and buy card skins.
  - We also added Static and Eternal stones. Those stones are used to upgrade cards and create new ones in the Forge. You will be able to Shred cards to obtain stones depending on their Blockchain state (Shredding static cards give static stones ; Shredding Flex or Eternal cards give eternal stones).
  - Both those items are available to be bought in the shop. You will also be able to trade Eternal Stones for Static Stones, and Trisel for Ark.
- New collection display
  - We completely reworked the way you look at your collection. It puts the focus on the art of the cards and will improve the accessibility of the craft by incorporating it directly into the card details.
  - We regrouped all cards into their respective set that contains all the classic cards of it. For each set, you will also be able to look at the Prestige version of the set containing all Special Rare, Exclusive and Unique cards of this Set.
  - In the same spirit as on the portal, when accessing the details of a card, you will first access the product version where you will be able to appreciate it full screen, apply a skin to all the versions of this card and read a bit of lore from this card. And then via the card stack, you will be able to access the details of a particular card to craft it.
  - Rift cards also come with beautiful new ways of enjoying the visuals of it. Firstly, the Foil effect has been reworked to be way more integrated into the art style of the cards. Secondly, a new type of skin has been added to be bought with Ark that enables a parallax effect to the card that adds depth to the Art!
  - The skin system is a new system introduced with this new collection. When you buy a skin for a card with Ark, you now buy it for every version of this card and not only for a specific one. For example, if you buy the Parallax skin of the Isalys standard card, you will be able to apply it to every copy of Isalys standard you own.
  - The craft system will arrive in a few weeks when everyone has been able to get their share of Rift cards.
    - Until it arrives, to make sure you have enough Trisel to upgrade all your cards, we have enabled a 50% boost to all Trisel gains until crafting is available!
  - The Forge is a new system that allows you to craft new Static or Eternal Cards. For static cards, you will only need Static Stones. For Flex cards, you will need Static stones and a Flex Roll (randomly gained from the Leaderboard and from the VIP system).
  - We removed the Bonus Roll functionality for Rift. If you have completed (10 packs of Flex cards opened), that you didn't claim, it has been automatically sent to your inbox. Not completed bonus roll will be lost.
  - You will now find completion targets for each set of cards. These objectives are validated as you collect new cards. Be careful though, if you sell or shred cards, you may lower your completion percentage and lose these rewards.
  - We have renamed some cards to better fit the Lore of the books. 
- Ranked season
  - A new Ranked season has started. We applied a soft reset to every player's rank: at the start of the new era, you will start two ranks below your current rank. (Bronze, Silver and Gold -> Bronze, Platinum -> Silver, Diamond -> Gold, Gladiator -> Platinum, Champion -> Diamond)
  - The Trisel multiplier for all ranks also applies to Ark gains.
  - We added Flex Rolls as rewards for Gladiator's and Champions and removed Flex packs and Flex cards so all flex rewards come from the Forge. 
  - New Ultra Rare and Mythic Shards of the Rift season are available as Leaderboard rewards. They will be able to be combined at a later date. 
- Rift Raids
  - Raids also get their own Rift version! You will face Powerful Rift cards and be able to earn Rift cards, Trisel, Ark and Gaming Points.
- We increased the odds of Static shards, Static packs so they are the same as their Flex counterparts.
