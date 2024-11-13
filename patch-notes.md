# Cross The Ages: TCG Early Access Patch Notes

## Direct Links

- 0.23
  - [0.23.11709](#02311709-patch)
  - [0.23.11379 Hotfix #1](#02311379-hotfix-1)
  - [0.23.11379](#02311379-patch)
  - [0.23.11351](#02311351-patch)
  - [0.23.11302](#02311302-patch)
  - [0.23.11252](#02311252-patch)
  - [0.23.11206](#02311206-patch)

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
