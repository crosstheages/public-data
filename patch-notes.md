# Cross The Ages: TCG Early Access Patch Notes

## Direct Links

- Upcoming
  - [Upcoming](#upcoming)
- 0.10
  - [0.10.3853](#0103853-patch)
- 0.9
  - [0.9.3688](#093688-patch)
  - [0.9.3616](#093616-patch)
  - [0.9.3528](#093528-patch)
  - [0.9.3447](#093447-patch)
  - [0.9.3431](#093431-patch)
- 0.8
  - [0.8.3322](#083322-patch)
  - [0.8.3271 Hotfix #1](#083271-hotfix-1)
  - [0.8.3271](#083271-patch)
  - [0.8.3264 Hotfix #1](#083264-hotfix-1)
  - [0.8.3264](#083264-patch)
  - [0.8.3192 Hotfix #1](#083192-hotfix-1)
  - [0.8.3192](#083192-patch)
- 0.7
  - [0.7.3069](#073069-patch)
  - [0.7.3061](#073061-patch)
- 0.6
  - [0.6.3012](#063012-patch)
  - [0.6.3006](#063006-patch)
  - [0.6.3004](#063004-patch)
  - [0.6.2925](#062925-patch)
- 0.5
  - [0.5.2838](#052838-patch)
- 0.4
  - [0.4.2704 Hotfix #1](#042704-hotfix-1)
  - [0.4.2704](#042704-patch)
  - [0.4.2673](#042673-patch)
  - [0.4.2666](#042666-patch)
  - [0.4.2607 Hotfix #1](#042607-hotfix-1)
  - [0.4.2607](#042607-patch)
- 0.3.0
  - [0.3.0.2492](#0302492-patch)
  - [0.3.0b](#030b-patch)
  - [Patch](#030-patch)
- 0.2.7
  - [0.2.7c](#027c-patch)
  - [0.2.7b](#027b-patch)
  - [Patch](#027-patch)
- 0.2.6
  - [0.2.6d Hotfix #2](#026d-hotfix-2)
  - [0.2.6d Hotfix #1](#026d-hotfix-1)
  - [0.2.6d](#026d-patch)
  - [0.2.6c](#026c-patch)
  - [0.2.6b](#026b-patch)
  - [Patch](#026-patch)
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

### Changes

- Duels
  - You can now report your opponent's name.
  - Opponent card placement is now animated.
  - Combo cards grade A or S will now show the cinematic of the character its arkhome is from.
  - Game window will now be put in foreground if you are in the queue and are matched.
- Cards
  - You can now purchase animation level 2 using your free animation or CTA Token otherwise.
- Loot
  - You now dynamically see how many chests left you need to unlock before getting slot #3.

## 0.11.3970 Patch

`2023-03-14 07:30 UTC`

### Changes

- Event
  - Arkhante event is now available until Thursday 06th April, 23:59 UTC.
  - New event missions have been added, they last for the whole event.
  - Completing them rewards you with Event Point which is a new progression system that we added.
  - You can also progress this system by doing your regular missions such as dailies and weeklies (amount varies) as well as winning duels (+125 per duel).
  - The progression is divided in 50 levels each requiring 500 Event Points.
  - Completed them awards you Trisel, Cosmetics and Event Coins.
  - Those Event Coins will be exchangeable in the upcoming Event Shop, planned for the 15th at 17:00 UTC.
  - You can earn additional rewards by buying Event Insignia which also unlock new special rewards in the shop. Keep in mind that the most rare items such as the new Exclusive Cards require the Insignia to be exchanged for.
  - During this Event there will be up to 7 Exclusive Cards, until the 22th there will be only 2 available. After this, other 5 will be available in the Event Shop as well as inside the Neo Arkhante Chest which will also release on the 22th at 17:00 UTC.
- Blockchain
  - Added a feature to link and unlink a Cold wallet. More details on the CTA Account application. Only supports MetaMask for now.
  - Added a feature to unlink your Game wallet (through Magic Link) if it is empty (no NFT on it). Once there is no Game wallet linked you can change your email.
  - Added a state to every Cross The Ages NFT showing if an asset is currently used in a pending burn or not, you might want to look at it before buying an asset.
- Tutorial
  - Updated the tutorial for the new gameplay.
- Play
  - Updated the display and behavior of the hand.
  - Now display both turns and arkhomes used for Elemental affix.
- Auth
  - Removed login method as for now only CTA account is available.
  - Regrouped forgot password and create account texts.
- Dashboard
  - Added a pop-up showing the notes when a new patch is out.
  - Added a pop-up showing when a new event is out.
  - Added some animation level 3 and 4 randomly on the dashboard.
- System
  - Renamed "Simple Affinity" into "Affinity" and "Double Affinity" into "Trinity".
  - Improved synchronization with IMX blockchain to be blazing fast.

### Fixes

- Play
  - Fixed an issue preventing SA and Cut-Scenes from being displayed.
  - Fixed various issues regarding affixes display.
  - Fixed an issue regarding the heptagram and the use of Shift Affix with Shift SAs.
- Cards
  - Rotation cards now display the correct potential based on their rank.
  - Collection sorting now mixes both field and battle card instead of splitting them, mostly relevant for arkhome sorting.
  - Added missing avatars.
- Crafting
  - Fixed an issue during a Power Up showing a field card as reagent along battle card and vice-versa.
- Auth
  - Removed the infinite loader while updating the birth date.
- System
  - Disabled hardware acceleration globally and disabled some animations based on your hardware device.
  - Fixed an issue regarding non-latin characters.
  - Fixed an issue with API connection showing constantly the API reconnection icon on client.
  - Fixed an issue preventing some NFT metadata to be reflected on-chain, this was especially the case during power-up.

## 0.10.3853 Patch

`2023-03-06 03:30 UTC`

### Changes

- Leaderboard
  - Season 1 Era 3 (S1E3) has ended, here are the rewards you all received depending on the recent highest rating you reached:
    - 0-1149: 1,000 Trisels + Weekly T1 chest
    - 1150-1349:  2,000 Trisels + Weekly T2 chest
    - 1350-1499:  3,000 Trisels + Weekly T3 chest
    - 1500-1649:  5,000 Trisels + Super chest
    - 1650-1799:  7,000 Trisels + Mega chest
    - 1800-1949:  10,000 Trisels + Ultra chest + 600 Prana
    - 1950-2099:  15,000 Trisels + Omega chest + 1200 Prana
    - 2100+:  25,000 Trisels + Neo chest + 2400 Prana
- Gameplay
  - Score computations has been changed, previously both simple and double affinities were counting in points now it is double only.
  - Cards in hand loop has changed, you now start with 4 cards, draw 1 each turn and can redraw up to 2 per game.
    - Note: It means that on your first playable turn you will have 5 cards in your hand.
  - Introducing a new system called affixes:
    - Affixes are game modified applied at the start of the game and slightly changes some rules of the game.
    - It is determined randomly at the start, some affixes depends on the rating you have.
    - There is 2 pools of affixes, one that is available for everyone and one that is available above 1700 rating only.
    - Here is the list of the first pool:
      1. Classic (unlocked at 0 rating): No game modifier.
      2. Elemental (unlocked at 1200 rating): A field of a random element is activated at a determined turn. You know when it will be activated but not which element. Lasts 2 turns.
         - Field strength: 30
         - If a field is already active, it will be overridden by this one.
         - When a player plays a field of his own, at the end of it we return to neutral.
         - 1 field activated turn rand(5-8), 1 field activated turn 10-13 (first rand + 5 : if first is activated at turn 5, the other is activated at 10 ; if 6, the other is activated at 11 ; ...).
         - Element and turn activation of the first field is announced at the start. Element and turn activation of the second field is announced after the decay of the first field.
      3. Score Twist (unlocked at 1250 rating): Modification of end score rand (55, 60, 70).
      4. Extended Reach (unlocked at 1300 rating): Chain starts at 2.
      5. Inspiring (unlocked at 1350 rating): All cards with the same Element as the leader gains 25 power.
         - If a player uses Banner of command, it stacks.
      6. Limited reach (unlocked at 1400 rating): Chain can't go above 1.
      7. Field Overflow (unlocked at 1450 rating): Fields are boosted by +25 power.
      8. Revolution (unlocked at 1500 rating): At the start of the duel, your leader is locked in your hand and can't be played until turn 7-8.
    - Here is the list of the second pool (1700+ rating):
      1. Classic: No game modifier.
      2. Blitz Game: 24 seconds per turn.
      3. Classic: No game modifier.
      4. Shift: same as SA SA_SHIFT_ADVANTAGES but for the whole duration of the duel. If you play a leader with shift advantage, it un-shifts for the duration of the SA.
      5. Classic: No game modifier.
      6. Golden Redraw: Only 1 draw at the start of the game.
      7. Classic: No game modifier.
      8. Affinity Stacking: When a card has 1 affinity, it gains power each turn.
         - Mode D, +20 (Adds 20 power every 2 turns starting at the end of next turn, once per card).
    - Affixes are shown at the start of the game through a dice roll, the number shown correspond to the number of the lists above. One affix means one dice, two affixes means two dices.
- User
  - Birthdate is now required. If you are not an adult in your country you might not have acces to crypto features depending on the law of your country.
  - Multi-session is now allowed between a game session (from the game) and any web application (such as CTA Account). You will no longer have to relog if you log in on a web application while using the game.
- Board
  - Updated every drop VFX.
- Auth
  - Completely reworked the flow and the look.
- Shop
  - Interface has been updated.

### Fixes

- Board
  - Cards details now correctly show field arkhome modifier.
  - Heptagram with double shift SA should now behave correctly.
- Crafting
  - Power up details window is now scrollable.

## 0.9.3688 Patch

`2023-02-28 10:30 UTC`

### Changes

- CTA Account
  - Added access to the shop.
  - Various visual updates.
- Tutorial
  - Added a skip button on the tutorial dialog.
  - Added a step to explain the field card and redraw.
- Loots
  - Updated opening interfaces.

### Fixes

- Loots
  - Updated prana bundle texts.

## 0.9.3616 Patch

`2023-02-22 07:30 UTC`

### Changes

- Blockchain
  - Smaller prana bundles are now available on the marketplaces.
- Loots
  - You now have to burn any NFT chest before seeing its opening animation.
- Shop
  - Added CTA tokens purchases on mobile.

### Fixes

- Tutorial
  - Fixed issue preventing players from going past the heptagram step.
- Cards
  - Fixed non-working filters related to owned/unowned cards.
  - Fixed issues with scrolling.
- Settings
  - Fixed an issue preventing settings to be persisted.
- System
  - Disabled hardware acceleration on all platforms until more crash fixes.

## 0.9.3528 Patch

`2023-02-19 08:35 UTC`

### Changes

- Blockchain
  - Any missing mint pass will automatically be minted on your next login.
  - Pending burns are now available on the CTA Account app (formerly called Bridge, url will change in the future but for now it will still be using the bridge one).
  - Assets section is available on the CTA Account app, it lets you browse your assets as well as transfer them without revealing your game wallet private key.
  - Awakening now burns & mint a new token instead of updating the previous one.
  - Prana bundles images have been updated to avoid mixing them.
  - Souvenir cards now have a Grade metadata showing from what bundle they are from (C from 100$, B from 250$, A from 500$).
- Shop
  - You can now buy CTA tokens when you have 10 or less remaining (was 0 previously but impossible to reach for a non-presale account).
  - CTA Tokens prices in Prana have been reduced until mobile payment. Users who bought them at higher prices between 11th and 15th will automatically receive the difference at the start of next month.
- Loots
  - You can now open up to one Standard, one Premium and one Legacy pack on the same account. You can still bridge as many packs as you want from Polygon on the same account.
- Perks
  - CTA Cap breakdown is now available in Perks.

### Fixes

- Blockchain
  - Bridge should no longer bug out with infinite loading time.

## 0.9.3447 Patch

`2023-02-11 17:30 UTC`

### Notes

We are aware of some issues regarding blockchain synchronization. We are working on it and will update you as soon as it is ready.

### Fixes

- Loot
  - Fixed an issue with the Prana Bundles text.
  - Fixed an issue with the Prana Bundles opening display.
  - Fixed an issue where cards could be reversed (we know you loved Reverse but it's now gone!).
- Heptagram
  - Various layout fixes.
- Interface
  - Fixed missing cursor on desktop platform.
  - Various texts update.
- System
  - Fixed an issue with initial loading when starting the application.

## 0.9.3431 Patch

`2023-02-10 15:30 UTC`

Disclaimer

Due to API limitations on the IMX side, we have to throttle our usage of the blockchain. As such getting all the NFTs when initializing your wallet can take some time, it is being done as a background task.
Also, whenever you need to burn tokens, it might take up to 1 min to get the information back from IMX, so please wait on the loading screen in-game while we are getting the information. If you cancel it (but your burn all went through), you will still have the content of your chest / the outcome of your card.

### Changes

- Wallet
  - As part of our migration from Stardust to Magic Link, we are now making the CTA Magic Link wallet available and required for any Web3 action.
  - Please see the notes at the end to have a guide based on your use case(s).
  - Using this non-custodial wallet, you can manage your assets however you want. Keep in mind that since it is non-custodial, you have the entire responsibility of your NFT and we will not be able to recover any wrong usage of them on the blockchain.
  - We have removed any plan for Trisel activation fee on transfer EXCEPT on the Minting Pass. Every Minting Pass is automatically activated when you open a PreSale Pack that contains it, although if you transfer it, including selling it, the new owner will have to activate it using Trisel in order to gain its benefit. Although there is no restriction on re-trading.
  - Keep in mind that the Magic Link solution is an intermediate step for us since we are working with Immutable X since the end of 2022 on the [Immutable X Passport](https://www.immutable.com/products/passport) that will be released later this year, CTA will be one of the first game to implement it as it will let many people onboard easily to Web3.
- Marketplace
  - The 3 largest Prana Bundles are now available on the marketplace, listed in USDC, with the same price as what it is in the shop (minus marketplace fee). Once bought, send it to your game wallet and you will be able to open it like a chest to get your Prana.
  - There is no supply for those Bundles, although our community has asked us for a way to make available the card we are releasing in our Prana Physical Collection. As such each card is available with a supply of 1000 and 100 (non-foil / foil respectively) whenever you will redeem it, as a souvenir. There are 10 different cards for each bundle, you get one randomly for each bundle consumed.
  - Those cards cannot be used in-game / in your deck and are purely for the collection.
- Duels
  - You are now warned if you are trying to enter a queue while it's disabled.
- Cards
  - Added arkhome to the deck export string in order to pick a proper combo card.
  - Exclusive cards for our private investors are now available. If you are eligible, please contact us with the wallet you want them to be transferred on.
  - Now display your NFT tokenId on card details if it is an NFT.
- Shop
  - CTA Token are now priced in Prana
    - Note: This change is due to Prana Bundle being available on IMX as NFT.
- Interface
  - We updated the heptagram to make it more clear.
  - Added a few animations.

### Fixes

- Cards
  - Fixed an issue with sorting in the collection.
- Leaderboard
  - Fixed a display issue with one dummy element.
- Loots
  - Added a message if you are trying to open two presale packs on the same account (it is restricted to 1).
- Settings
  - Fixed various issues with how settings were saved.
- Auth
  - Fixed display issue in register email.
- System
  - Fixed an issue slowing down the servers between 00:00 and 08:00 UTC.
  - Fixed various crash and disconnect loops.

### Notes

Here is some guidance about CTA x Magic Link and the use cases in our game:

- I want to **mint / craft / bridge / open NFT**:
  - You need to initialize your Magic Link wallet.
  - Before starting, double check that the email of your game account is the one you want to use.
  - If not, you can change it in-game in your settings.
  - Then simply go to our [Bridge Application](https://bridge.cta-tcg-live.com/).
  - When you log in, you will be prompted with CTA Magic Link wallet initialization.
  - Follow the Magic Link steps.
  - That's it! You're all set up.
  - For burn operation, you will be redirected to Magic Link in order to validate the transaction.
- I want to **buy NFTs on the marketplace** with my **own wallet** (not CTA Magic Link):
  - You do not need Magic Link for that, any IMX-compatible & enabled Wallet will let you go on the marketplaces.
  - Once you have bought the NFTs, if you want to play with them you just have to send it to your CTA Magic Link wallet, its address is displayed on the bridge once initialized.
- I want to **transfer** or **sell** my NFTs:
  - In order to do so, you will have to reveal your private key.
  - Once initialized, click on the "Revel" button in the home page of the Bridge.
  - You will be redirected to the CTA Magic Link Reveal page where you will get your private key.
  - KEEP IN MIND THAT PRIVATE KEY GIVE TOTAL CONTROL OF YOUR WALLET TO ANYONE WITH IT, AS SUCH WE RECOMMEND YOU TO STORE IT SECURELY IF YOU DO SO.
  - Import your private key to any IMX-compatible wallet (GameStop Wallet or MetaMask).
- I want to change my **CTA Magic Link wallet email address**:
  - This use case is not available yet, we expect to release it before the end of February (Change Email).
- I want to **link my own wallet to my game account**:
  - This use case is not available yet, we expect to release it before the end of February (Cold Wallet).

Keep in mind that we are currently reworking our Bridge application to be more than that and be your CTA Account Application.
We will both expand its features as well as its UX/UI.
We are also intending to release our own online Shop (to buy Prana on the web using Credit Card) as well as our own Marketplace with custom display and no marketplace fee.

Fees:

- 2% IMX (protocol)
- 3% CTA (creator)
- x% Marketplace -> this one vary based on the marketplace you are trading

## 0.8.3322 Patch

`2023-02-06 19:30 UTC`

### Changes

- Tutorial
  - Added a new tutorial showing you every basics of the game.
  - Anytime we make a gameplay update, it will be updated and you will be able to replay it.
  - Once played, you can replay it using the burger menu on the dashboard.
- Duels
  - Added custom options to choose hand size / draw & redraw count:
    - Size is the number of cards you have when starting the game. Default: 5, Min: 2, Max: Compound
    - Draw is the number of times you draw a card, starting on the first turn and each subsequent turn. Default: 8, Min: 0, Max: 8.
    - Redraw is the number of times you can discard a card to get a new one, you get this amount at the beginning of the duel. Default: 2, Min: 0, Max: 3.
    - You need to have/draw at least 10 cards in order to have valid parameters.
    - You cannot have + draw + redraw more than the maximum of a deck (20).
  - Splitted affinity score in simple and double. For now the default is 1 for both (no change from previous patch) but you can now change it as you prefer in custom. Keep in mind that a card counted with a double is not counted with a simple.
  - Special Ability visual effect no longer goes beyond board border.
- Cards
  - Auto update training deck with rotation cards using auto deck feature in order to make a more competitive deck.
  - Added an indicator explaining that the filter panel can be scrolled.
- Leaderboard
  - Removed the draw indicator since it is no longer really relevant with score game mode.

### Fixes

- Duels
  - Fixed opponent leader not showing on versus screen.
  - Fixed an error while exiting a scene where the heptagram is shown.
  - No longer close the card details panel on the last turn except if open on mobile.
- Shop
  - Fixed an error occuring while interacting with pop-ups.
  - Fixed an error related to daily, weekly and reward chests.
  - Fixed discount showing up on Prana bundles.
- Loots
  - Updated Shop Passes names.
- Interface
  - Various text updates.
  - Fixed various images of bleeding artifacts.
- System
  - Fixed many crash occurrences.
  - Fixed an error preventing some input fields from being completed.

## 0.8.3271 Hotfix #1

`2023-02-03 06:45 UTC`

### Notes

- We are aware of issues, mostly crashes, that arise in 0.8.3264 Patch and are actively working on those. We are looking to deploy a new client-only patch later this week, hopefully today.
- Considering how our last update prevented players from making their daily mission, either from crashes or gameplay changes, we dropped to everyone who has Early Access 500 trisels directly on your account.

### Changes

- Duels
  - Reverted changes to the hand, it is now working like before (start with 10 cards in hand and 3 redraw).
  - Player time is now 5 mins starting from gold rating (>= 1500), was platinum rating before (>= 1850).

## 0.8.3271 Patch

`2023-02-02 13:30 UTC`

### Fixes

- Shop
  - Fixed an issue preventing desktop clients from buying prana.

## 0.8.3264 Hotfix #1

`2023-02-02 12:30 UTC`

### Fixes

- Auth
  - Fixed an issue preventing older clients from logging in (mostly relevant for mobile).

## 0.8.3264 Patch

`2023-02-02 11:30 UTC`

### Changes

- Duels
  - Changed the number of cards available when starting a duel, it now work as follow:
    - 6 cards in your starting hand, down from 10.
    - On your first turn you get a redraw, on the next you draw. And then it alternates up to the last turn.
    - In total you can see up to 6 + 4 + 4 = 14 cards from your deck, up from 13 (10 + 3).
    - Notes: On older clients you might see your redraw count starting at 3 and then changing back to 1 or 0 on next turn, it is only visual as it is working as explained above.
  - Added penalty on Trisel gains after a duel in order to reduce incentive from giving up:
    - Defeat has a 33% penalty on trisel gained. I.e.: if you scored 50 and earned 25 trisel before, you will now earn 16 Trisel instead. Keep in mind that every computations are always rounded down.
    - Surrender has a 66% penalty on trisel gained, example: if you scored 50 and earned 25 trisel before, you will now earn 8 Trisel instead. Keep in mind that every computations are always rounded down.
- Loots
  - Reworked the interface.
  - The new interface now shows what Shop Pass is active on your account, if you do not have any you will be able to buy a one in the shop in an upcoming update (mostly relevant for Standard pack owner / Road to GA players).
  - As a reminder, those passes are what give you more unlock chest slots. They also have been renamed to reduce confusion with minting passes (such as the Golden one) and player ranks on the leaderboard (bronze, silver, gold, ...). New names are:
    - Iron -> Topaz (1 extra slot, auto-activated on Apprentice during EA)
    - Bronze -> Amethyst (2 extra slots, auto-activated on Disciple during EA)
    - Silver -> Sapphire (3 extra slots, auto-activated on Primus during EA)
- Shop
  - Added a confirmation checkbox on early access CTA Token discount usage when buy a CTA Token bundle.
- Auth
  - Add visual feedback whenever your login attempt is being processed by the server.

### Fixes

- Play
  - Fixed buff/debuff tooltip display.
- Cards
  - Made the details scrollable giving back access to the mint button on mobile.
- Auth
  - Various fixes in sign-up form.
- Interface
  - Various text updates.
- System
  - Various sound effects fixes.
  - Fixed crashes happening due to connection loss.

## 0.8.3192 Hotfix #1

`2023-01-30 15:45 UTC`

### Fixes

- Bridge
  - Fixed an issue preventing Legacy packs to be bridged.

## 0.8.3192 Patch

`2023-01-30 11:30 UTC`

### Changes

- Duels
  - Points gained by a capture increased from 1 to 2.
  - Score threshold increased from 50 to 65.
  - Trisels gained per duel are now based on your score. You get roughly half the points you scored at the end of the game (no matter if it is a victory or not) with a maximum of 35. It is then increased up to 100% based on your rating.
  - Trisels gained per duel has a rolling daily cap of 500 Trisels over the last 30 days, increased up to 50% based on your rating. Cap each day is updated only if you open the game (but you do not need to play).
  - Experience gained per duel is now based on your score. You get roughly half the points you scored at the end of the game (no matter if it is a victory or not) multiplied by 10 with a maximum of 350. It is then increased up to 100% based on your rating.
  - Removed any queue restriction from early surrender or disconnect.
  - Added a new card details panel.
- Dashboard
  - Now tell you if you do not have Early Access how you can move forward.
- Loots
  - NFT packs opening is back.
- Crafting
  - NFT cards crafting is back.
- Settings
  - Added a setting to control cutscenes behavior.
- System
  - Added various SFX.

### Fixes

- Duel
  - Fixed an issue preventing the player from putting a card on the board if he disconnected after a redraw.
- Cards
  - Cannot add unowned cards to the deck anymore.
- Crafting
  - Various fixes.
- Settings
  - Fixed an issue preventing language change.
- Interface
  - Various texts update.

## 0.7.3069 Patch

`2023-01-23 05:30 UTC`

### Changes

- Duels
  - Score indicators (text and bar) have been updated to be more visible.
  - Swap turn banner has been moved below the header to prevent hiding score changes.
  - No longer hide card details on the last turn except on mobile.
- Profile
  - History has been adjusted for mobile screens.
- System
  - Increased scroll sensitivity across the board.

### Fixes

- Duel
  - Fixed an issue where draw was not issued when it should have been.
  - Missing audio sound during turn 6-7 is now back.
- Cards
  - Unowned cards are not showing a quantity of 0.
- Profile
  - Emotes are back.

## 0.7.3061 Patch

`2023-01-20 10:30 UTC`

### Changes

- Leaderboard
  - Season 1 Era 2 (S1E2) has ended, here are the rewards you all received depending on the recent highest rating you reached:
    - 0-1149: 1,000 Trisels
    - 1150-1349:  3,000 Trisels
    - 1350-1699:  7,000 Trisels and a Mega chest
    - 1700+: 15,000 Trisels and a Mega chest + an Ultra chesteveryone started at 1200, as such it has been put at 1250.
  - In addition to this and considering there have been a lot of bugs hunting, especially on mobile release, we added a bonus for anyone who opened his pack before the end of this era, as follow:
    - Standard: 100 Trisels
    - Apprentice: 1,000 Trisels
    - Disciple: 2,500 Trisels
    - Primus: 5,000 Trisels
- Event
  - Lunar New Year event is now available until Thursday 9th February, 11pm UTC.
  - New event missions have been added, they last for the whole event.
  - Completing all of them rewards you with an event chest with rewards containing up to 2 Ultra Rare cards and 1 Exclusive card for accounts with a cap higher than 100 CTA Token.
  - Lunar Neo is available in the shop, it contains the same base as Neo but adds a guaranteed Exclusive card and an exclusive Cosmetic reward (if you did not have all the event Cosmetics already).
  - Lunar Omega is also available in the shop, it contains the same base as Omega but adds a guaranteed Exclusive card and an exclusive Cosmetic reward (if you did not have all the event Cosmetics already), limited to 3 purchases only.
  - You can also earn the Exclusive card by winning games, rules are as follow:
    - You can earn up to 1 Exclusive card after a ranked game.
    - You need at least 1150 rating at the end of the game to be eligible.
    - Odds to get Phoenix Exclusive after a duel is now as follow:
      - 1150-1349 rating: 0.25% on win, 0.13% on draw
      - 1350-1649 rating: 0.5% on win, 0.25% on draw
      - 1650+ rating: 0.75% on win, 0.38% on draw
  - The card exists in Standard and Alternative. You cannot craft it at all, the outcome (rank/grade) is random when you obtain it and definitive. Foil odds are the same as usual (10%), grade odds follow the base (70/22/7/1 respectively) ones, rank distribution is uniform.
  - List of all the Cosmetic rewards:
    - 2 avatars obtained (automatically with the cards)
    - 2 avatar frames
    - 1 profile banner
    - 1 in-game footer
    - 3 emotes
  - Dashboard features a new background.
- Duels
  - Win condition for turn 16 has been replaced with a score system, the player with the highest score wins the game. If both players have the same score, it is a draw.
  - Added a new win condition, if a player reaches a score of 50 or higher he immediately wins the game. In case both players have more than 50 points, the one with the highest win. In case of the same score on both sides, it is a draw.
  - Score is gained as follow:
    - +1 point per card captured
    - +1 point per card that have at least one affinity
  - Score is computed on each turn for both players
  - Score is displayed on a bar for each player, you can interact with it to see the breakdown of your score.
  - Game duration is now 6 mins per player up to 1850 rating, starting from 1850 rating it is 5mins.
  - Affinity Stacking is no longer active.
- Blockchain
  - We migrated the collection from Stardust to our own. Wallet will be using non-custodial Magic Link instead of custodial Stardust.
  - Previous collection: <https://immutascan.io/address/0x8e3c7e22566983e1ede005762a6afab6bdf28277>
  - New collection: <https://immutascan.io/address/0xa04bcac09a3ca810796c9e3deee8fdc8c9807166>
  - This migration is quite huge as it involves 250k NFT, every NFT is handled automatically except Bored Box which will have a separate way to be migrated.
  - Here is the breakdown of each steps that will be happening in the next following days and weeks:
    - Put the bridge offline.
    - Deploy the new collection and mint every NFT from the Stardust collection (with numbering split).
    - PreSale packs are also all re-minted and those opened are burned (to maintain consistency with Polygon collection).
    - Burn all Stardust NFT except Bored Box
    - Unplug Stardust from the game
    - Put back online the game
    - Re-enable features one by one (should last up to 1 week up to step 4):
      1. Enable mint only (no NFT pack opening nor NFT crafting)
      2. Enable burn (NFT pack opening + NFT crafting)
      3. Re-activate the bridge
      4. Enable Magic Link initialization (put all NFT on player wallet which make transfer and marketplace available by exporting the seed)
      5. Add crypto payments
      6. Add "cold wallet" feature
      7. Add in-game marketplace
      8. Enable chest minting
- Cards
  - Presets are now limited to 25.
- Missions
  - Added 3 new types of missions.
  - Removed the mission related to previous game mode, if you had it in your weekly quests it has been automatically completed.
    - Note: There was a bug that instead of completing this mission it completed all the missions, lucky you, we will not revert it so feel free to claim them (you would have done them anyway!).

## 0.6.3012 Patch

`2023-01-19 08:15 UTC`

### Fixes

- Duel
  - No longer show red warn screen nor red timers on reconnection.
- Cards
  - Fixed an issue preventing the deck to be saved.
- Profile
  - Banner and In-Game Footer are now in their own section.

## 0.6.3006 Patch

`2023-01-18 14:00 UTC`

### Changes

- Profile
  - Highest Rating is now the Recent Highest Rating.

## 0.6.3004 Patch

`2023-01-18 10:30 UTC`

### Changes

- Duels
  - Now show Training and Rotation ribbons on cards in-game.
  - Show a blinking cinematic icon during cinematic in case it is hidden or skipped.
- Cards
  - Added a setting button for the current deck.
    - Let you customize the deck name and card back to use (not available yet).
    - Show you your cards arkhome & power repartition.
- Crafting
  - Filters are now available.

### Fixes

- Duels
  - No longer prevent player from playing his cards if starting player and have to reconnect.
  - No longer wrongly display the starting player timer at the start of duel.
  - Fixed an issue preventing music from being played on some turns.
  - No longer highlight the draw stack if not available.
- Cards
  - No longer can close card details on desktop layout.
  - Card ribbons (training / rotation) text is now correctly displayed.
  - Stacking filter setting is now saved in presets.
  - Various fixes on the auto deck feature.
  - Various display fixes.
- Loots
  - Cards recap at the end of an opening no longer show blank cards.
- Crafting
  - Various display fixes.
- Shop
  - Added missing texts.
- Missions
  - Fixed a rare issue preventing missions to be renewed right after a login.
- Profile
  - WalletID is no longer displayed on two lines on mobile.
- Settings
  - Added a setting to enable/disable hardware acceleration. Some low end devices might prefer software rendering.
- System
  - No longer show disconnected notifications when logging out.
  - Fixed multiple issues regarding connection loss.

## 0.6.2925 Patch

`2023-01-12 04:30 UTC`

Known Issues (do not report this, we are working on it)

- Duel
  - If you are player 1 and have to reconnect to the game, you might not be able to play your cards.
- Loots
  - Cards recap after an opening might show blank cards.

### Changes

- Duels
  - Draw no longer changes the rating (+0/-0) based on rating difference, it is now neutral for the rating. Rating has been recomputed since the start of the era following this change.
  - Reworked the management of the connectivity in order to better track if you were disconnected.
- Cards
  - Auto deck now considers your fields (if you put any) in addition of your Leader and SA.
  - Increased the size of the card on card detail outside of the game.
  - Reworked the card count icon to show it as clickable as well as increasing its size to better read the text inside it. Hitbox is bigger too.
- System
  - Updated the contrast of some icons.
  - Updated the global footer to make it more clear.
  - Updated various interfaces.
- Dashboard
  - ESC now opens the burger menu.

### Fixes

- Duels
  - No longer show a buff for Power Stacking SA, buffs are only shown for global effects.
  - Player time left on reconnection is now synchronized back with the server.
  - Affinity stacking default values have been updated for custom games.
  - No longer make the player enter in a coin toss -> 10s timer -> coin toss -> etc. loop.
  - Music cracking noise has been removed.
- Cards
  - Fixed an issue where the auto deck was adding cards not owned and then preventing the deck to be saved.
  - Auto deck now has an icon.
  - No longer let you think you can mint Training / Rotation cards.
- Crafting
  - Now show alternative card image possibilities on awaken.
  - Correctly update the selected card on power up.
- System
  - Now show you an error if you are trying to redeem a code without having access to the Early Access.
  - Loader cards are no longer blank.

## 0.5.2838 Patch

`2023-01-09 06:00 UTC`

Known Issues (do not report this, we are working on it)

- Crafting
  - Some interfaces might not be fully responsive / slow to respond.
- System
  - Some images might not load correctly.

### Changes

- Duels
  - Rating gain for a draw is now the normal formula but at a 50% rate. The player with the highest rating is considered as the loser. Rating for every player has been fully recomputed using this formula in order to remove the inflation from the previous formula present on the leaderboard.
    - Note: Your rating was lowered by this change, this is normal as the previous one was over-inflated. Keep in mind that if we did not do that, we would have to increase the threshold of rewards for the majority + draw abusers would get way more rewards than what they deserves.
  - Your highest MMR is now computed based on your games during the last 7 seven days, updated daily.
  - If you have more than 1850 rating and you do not play for more than 7 days, you will lose 50 rating per threshold (1850 / 2200 / 2550) per non-played week.
  - Affinity stacking has been adjusted as follow:
    - +20 power on [450, 545] cards
    - +15 power on [550, 645] cards
    - +10 power on 650+ cards
- Cards
  - UI has been entirely revamped.
  - You can now filter and sort your collection.
  - You now have an "auto" button that makes a deck based on your SA and Leader.
  - Exclusive Locke is now playable, keep in mind as since it is a skin you cannot play the normal Locke and the exclusive one. This does apply for any card skin that will be available in the future.
- Crafting
  - UI has been entirely revamped.
    - Note: Filters from the collection will be added at a later date, performance will be improved too.
  - You now have an "auto" button for power up. It will automatically consume eligible duplicate cards at 0 potential from highest to lowest numbering in order to reach the rank you set.
- Auth
  - Your last email used is now saved.
- System
  - Game accounts no longer need to be whitelisted for mobile access.
  - Now recommend you to switch to Wi-Fi if you have data to download and are on roaming internet access.
  - You can now disable fields and cards animation, you might want to enable those settings on low-end devices.

### Fixes

- Duels
  - Correctly skip coin toss / 10s timer on reconnection during turn 1.
  - Correctly remove you from the queue if you leave quickly before entering it.
- Cards
  - Fixed an issue where cards from the Christmas Event Missions Chest had incorrect rank/potential.
- Profile
  - Correctly show AFK / Surrender stamps text.
- System
  - Various adjustments for smartphone notches.

## 0.4.2704 Hotfix 1

`2022-12-25 04:00 UTC`

### Changes

- Duel
  - Odds to get Locke Exclusive after a duel is now as follow:
    - 1150-1349 rating: 0.5% on win, 0.25% on draw
    - 1350-1649 rating: 1% on win, 0.5% on draw
    - 1650+ rating: 1.5% on win, 0.75% on draw
- Cards
  - Locke Exclusive illustrator is now unveiled.

## 0.4.2704 Patch

`2022-12-24 17:00 UTC`

### Changes

- Play
  - Limit Game Resources option now replaces Animated Field by Static Field. Use it on low-end devices.
- Cards
  - Locke Exclusive Standard and Alternative are now revealed.
- System
  - Warn you when new downloads are available and you are not on Wi-Fi to prevent extra charges.

### Fixes

- Play
  - Buff/Debuff tooltips are now clamped to the screen.
- Dashboard
  - Event text is translated.
  - Game mode dropdown text has been adjusted.
- Cards
  - Power on cards is no longer aliased while being visible on very bright cards (such as Calyps Alternative)
- Loots
  - The notification indicator is now back.
- Craft
  - Confirm button is accessible on mobile with notches.
- Profile
  - WalletID and Immutascan links are working again.
- Interface
  - Notch adjustments on iOS have been slightly modified to reduce distance from the home button.

## 0.4.2673 Patch

`2022-12-22 21:00 UTC`

### Fixes

- Cards
  - Power font has been adjusted to reduce aliasing.
- Shop
  - Payment link is now selectable and can be copied.

## 0.4.2666 Patch

`2022-12-22 14:30 UTC`

### Changes

- Duels
  - You can now directly see Exclusive Card Details from the ending screen.
- Cards
  - Power on cards now have a stronger outline making them easier to read on some bright cards.
- Shop
  - Added the payment link in the popup that is opened whenever you are trying to buy Prana / CTA Tokens in order to manually open the page in case the auto-open fails.
- System
  - Added support for mobile notches.
  - Changed minimum versions for several platforms:
    - Windows: 10+
    - macOS: 11.3+ (Big Sur)
    - Android: 10+
    - iOS: 14+

### Fixes

- Duels
  - Updated queue cancel logic to avoid being pulled into a game while the queue should have been canceled.
  - Heptagram can now be toggled without issue.
- Loots
  - Christmas Event Chest and Christmas Neo Chest now correctly show Exclusive cards while revealing them one by one.
- Craft
  - Correctly filter valid rarity on Power Up.
- History
  - Rating is no longer shown for custom games.
- Auth
  - Automatically trim spaces from input such as email whenever invalid, mostly relevant for Android.
- UI
  - Various layout fixes for mobile.
  - Various text updates.
  - 2D assets are no longer too bright on Android.
- System
  - Fixed various crashes.

## 0.4.2607 Hotfix 1

`2022-12-21 04:30 UTC`

### Changes

- Duel
  - Matchmaking has been adjusted to widen a little bit quicker the rating, max is now 2 mins from 2 mins and 30 seconds.
  - Matchmaking rating widening range is now up to +- 700 before being uncapped (up from 400 before being uncapped).
    - Note: Rating gain is (and always has been) capped at 400 rating diff. So if a player at 1800 plays against someone <= 1400, he will have the same gain/loss as if it was 1400 so does his opponent (his rating +400).
- Profile
  - Total cards and Total power now count only one value per card.
    - We show only unique id owned (if you have 3 Solis, we only count 1).
    - We count only the biggest power (if you have Solis Alt S and Solis Alt C, only the Alt S is counted).

### Fixes

- Cards
  - Locke exclusive power is now correctly computed.
  - Illustrators of Alternative and Combo cards are now correctly displayed.
- Reset
  - Daily/Weekly/FreeRotation are now more reliable as they are triggered as soon as you interact with the server rather than specific events.

## 0.4.2607 Patch

`2022-12-19 07:00 UTC`

### Changes

- Event
  - Christmas event is now available until Monday 9th January, 8am UTC.
  - New event missions have been added, they last for the whole event.
  - Completing all of them rewards you with an event chest with rewards containing up to 2 Ultra Rare cards. It also contains a guaranteed Exclusive card and an exclusive Cosmetic reward.
  - Christmas Neo is also available in the shop, it contains the same base as Neo but adds a guaranteed Exclusive card and an exclusive Cosmetic reward (if you did not have all the event Cosmetics already).
  - The Exclusive card artworks are masked, it will be revealed on Christmas Day (December 25th).
    - Note: You cannot play with it until the 25th. If you mint it before the 25th, it will have the mystery artwork that will not be updated after the 25th. We are in the process of moving out of Stardust so we will not fix it until the migration has been done.
  - You can also earn the Exclusive card by winning games, rules are as follow:
    - You can earn up to 1 Exclusive card after a ranked game.
    - You need at least 1300 rating at the end of the game to be eligible.
    - If you are the winner, you have 1% to get it. If it is a draw, each player has 0.5% to get it.
  - The card exists in Standard and Alternative. You cannot craft it at all, the outcome (rank/grade) is random when you obtain it and definitive. Foil odds are the same as usual (10%), grade odds follow the base (70/22/7/1 respectively) ones, rank distribution is uniform.
    - Known Issue: Alternative versions all have the same power (grade is not taken in account), it is something that will be fixed at a later date.
  - List of all the Cosmetic rewards:
    - 2 avatars obtained (automatically with the cards)
    - 3 avatar frames
    - 1 profile banner
    - 1 in-game footer
    - 2 emotes
  - All the cosmetic rewards cannot be NFT right now but it is something that we are considering in the future.
  - Dashboard has some snow showing up to celebrate the winter.
- Gameplay
  - Affinity Stacking
    - Nerf: Now is triggered at the start of your turn with a value a +20 (instead of the start of every turn with a value of +10).
  - Field Influence SA
    - Nerf: Deck cost reduction is now scaled based on the field power, i.e. at 50 it is -0, at 150 it is -100.
- Duels
  - Updated the default in-game footer.
  - Slightly slowed attack attempt animation.
  - Persisting global effects such as SA or Fields are now shown directly on the board, per player.
  - Fields are now animated on the mobile.
  - Heptagram is now half-transparent on mobile.
  - Added a system to detect if the client missed an event (such as swap turn), if it happens it will automatically trigger a reconnection without restarting the application.
  - Ending a game on a draw will now count towards the win progress of missions.
- Cards
  - Free rotation has been updated to include at least 3 strong cards. Battle cards can now have their rank and grade tweaked to reach a power target more or less balanced for every player.
  - Updated multiple level 1 animation.
- Leaderboard
  - Now display draws count in addition to win/loss. Draw is neutral for win rate %.
    - Known Issue: Draw count is shown as 0, will be fixed in a later patch.
- System
  - Reduced the size of various assets.
  - Added a higher definition of assets for Retina / 2k+ displays.

### Fixes

- Duel
  - No longer play multiple alert sounds on the versus screen.
  - No longer wrongly restricts from matchmaking a timed out player.
  - Field swap no longer shows a black screen on mobile.
  - No longer play sounds nor coin toss nor timer during a reconnection.
- Cards
  - Removed card backs at the end of Collection / Opening.
- Profile
  - Fullscreen resolution is now persisted correctly.
  - No longer show resolution settings on mobile.
- User Interfaces
  - Various fixes on mobile.
- System
  - Various crash fixes.
  - Changed some animation rendering process to avoid unexpected blank/green texture.

## 0.3.0.2492 Patch

`2022-12-10 17:30 UTC`

### Changes

- System
  - Versioning now includes build number, in an upcoming update the build number will replace the patch one which is the 3rd argument (`0.3.0.2492`-> `0.3.2492`).
  - Added a "Reset" button on the splash screen. Do not use it unless you have some issue with the game data, if you do it will close the game and re-download everything on next launch.

### Fixes

- Dashboard
  - Game mode dropdown is now working again.
  - Missions are no longer shown as locked.
- Leaderboard
  - List is once again visible.
- System
  - Fixed an issue preventing some light from being added to effects.

## 0.3.0b Patch

`2022-12-10 09:30 UTC`

### Changes

- Settings
  - Added an option to limit game's resources for low-end devices.
- System
  - Lowered some graphics requirements from the game.
  - Reworked the launch of the application in order to pre-load some needed assets as well as being more explicit of the tasks being done in the loading progress bar.
  - Various UI updates for small resolutions.

### Fixes

- Duel
  - Custom duels now have a value of 10 for affinity stacking.
  - Fixed an issue where multiple SFX could be played at once when a card was played.
- Cards
  - Deck cost deck with Field Influence SA should no longer wrongly warn about incompatible deck (due to new SA deck cost reduction) despite being valid.
  - Loading screen with cards no longer shows a blank card.
- Loot
  - Reward chest not unlocked/opened since more than a few weeks can now be unlocked/opened.
- Dashboard
  - Fixed an issue that made the queuing time from the dashboard longer than expected (up to 15s).

## 0.3.0 Patch

`2022-12-09 05:30 UTC`

### Changes

- Leaderboard
  - Season 1 Era 1 (S1E1) has ended, here are the rewards you all received depending on the highest rating you reached:
    - 0-1249: 1,000 Trisels
    - 1250-1499:  3,000 Trisels
    - 1500-1849:  7,000 Trisels and a Mega chest
    - 1850-2200: 15,000 Trisels and a Mega chest + an Ultra chest
    - Note: In a previous communication, we said that the first threshold was 1150 but it was incorrect as since it's based on ATH everyone started at 1200, as such it has been put at 1250.
  - In addition to this, the first 10 players who reached 2,000 rating (2k Challenge) received those rewards:
    - 1st:        20,000 Trisels and a Neo chest
    - 2nd:        15,000 Trisels and an Omega chest
    - 3rd:        10,000 Trisels and an Ultra chest
    - 4th to 10th: 5,000 Trisels and a Mega chest
  - New era starting rating is now 1100, as a consequence floor rating for matchmaking is now 1000.
  - Note: End of era rewards will not be based on the highest rating, it will instead be based either on current rating or a new system called "average rating", in any case it will be announced weeks before the end of the next era.
- Gameplay
  - Disclaimer: All the changes below are part of our set of balance changes for the S1E2, although keep in mind that anything can be adjusted in the future.
  - A new system "Affinity Stacking" has been added to the game:
    - After each turn, each card affected by at least an affinity will gain +10 power.
    - Losing one affinity does not reset this bonus, losing all of them does.
    - Capture does also reset the affinity stacking bonus.
  - Special Abilities
    - We are renaming "Special Attack" to "Special Abilities" as some of them are not directly related to Attack.
    - Affinities Reinforcement
      - New SA: "As long as you own your Leader on the board, every card you own with at least one affinity has a power up of +20."
      - Note: This bonus is independent from the "Affinity Stackig" system.
    - Shift Advantages
      - New SA: "When played, your Leader shifts the Arkhomes advantages, +150 becomes -150 and vice-versa. Lasts 3 turns."
    - Banner of Command
      - Buff: "As long as you own your Leader on the board, empower the Leader by +15 and all owned cards of the same Arkhome as your Leader by +45."
    - Field Influence
      - Buff: "As long as you own your Leader on the board, empower your field cards by +50 and weaken opponent field cards by -40. Your fields have -100 deck costs."
    - Power Stacking
      - Nerf: "For each turn elapsed and while you keep your Leader in your hand, its power is increased by +10 per turn."
      - Note: Previously the power increase was effective starting from turn 1 or 2, now it's from turn 3 or 4.
- Duel
  - All alert sounds have been updated (matchmaking, first and second alert for AFK / Timeout).
  - Coin toss bad luck protection no longer takes into account more than 2 games.
    - Note: Since our matchmaking does not consider your history of coin toss, reducing the number of games that weigh the toss reduces the probability of big streaks. In the future (when more players will be playing) we might revisit this system by adding it as a condition to match players together.
  - Leader Arkhome is now shown in the header with its usual icon.
  - Some effect durations have been shortened in order to speed up games.
    - Note: We are continuously working on in-game effects and planning to add new effects / rework some effects. As such some duration might be adjusted when such updates will come out.
  - A new outcome for a game has been added, before whenever the game ended by a 50/50 the lowest remaining time player would lose. We changed this behavior for ranked games as such:
    - Whenever a 50/50 happens, both players earn a reward chest and they split Trisels (15 Trisels each baseline).
    - If both players have a big enough rating difference, the highest rated player has no change on its rating, the lowest rated player does earn half the rating gain he would have earned on a win.
    - If both players are close enough in rating, no changes are made to their rating.
  - Trisel and Exp gains have been adjusted to let you earn more under some circumstances:
    - You get an extra 10 Trisel / 100 EXP if you own more than 90% of the board on a win.
- Mission
  - Missions are now randomly chosen from a pool for each player.
  - We added two new types of missions, playing and winning with a leader of a given Arkhome, available both daily and weekly.
- Cards
  - Free rotations are now randomly chosen from a given pool for each player.
    - Note: We are still iterating on this, both in terms of the number of cards but also what cards. Expect some changes in the upcoming weeks in this regard.
- Dashboard
  - Player name is now shown in the header.
  - Added a logout entry on the burger menu.
- Profile
  - Grayed out unavailable social accounts link (Apple, Google, Facebook, Twitter).
- History
  - Leader Arkhome is now displayed.
  - Duel date is now displayed.
  - Added draw outcome and updated some texts.
- Heptagram
  - Is now permanently displayed in every menu while on desktop layout. You can still toggle settings while in-game if needed.
  - If Shift Advantages SA is played, the Heptagram will be shifted while the effect is active.
- Loot
  - No longer show a blank screen but a wait screen if you skip the opening and not all packs are ready to be opened.
  
### Fixes

- Mission
  - Fixed an issue where opening a chest would count double toward the opening mission.
- Dashboard
  - Improved animation performances.
- Profile
  - Fixed an issue preventing the profile to be opened.
- History
  - Fixed an issue where the wrong leader was shown on some games.
- System
  - Fixed several issues regarding crashes and memory hog.

### Notes

- This release also features mobile versions for OGs, Moderators and Testers.
- Keep in mind that there are multiple display issues and that we are not looking for feedback on those, we are ONLY looking for blocking issues such as crash / cannot start / blocked in a menu / etc...
- All the visual details are being polished for every resolution, no need to report them at this moment.

## 0.2.7c Patch

`2022-12-05 00:30 UTC`

### Fixes

- System
  - Fixed an issue preventing launch on some devices.

## 0.2.7b Patch

`2022-12-04 23:30 UTC`

### Fixes

- Duels
  - Deck cost of the player is now correctly displayed.
  - End of the game will correctly wait for all visual effects to end.
- Cards
  - Various selection fixes.
- Crafting
  - Fixed an issue where NFT card would not be selectable.
  - Various layout fixes.
- System
  - Visual effects on macOS are back.
    - Note: We re-implemented temporary the old way to render them.

## 0.2.7 Patch

`2022-12-04 10:15 UTC`

- User Interface
  - The navigation between menus has been simplified with a static footer menu allowing you to move quickly from one menu to another.
  - Dashboard has been updated with new buttons and animation.
  - Shop, Collection and Crafting views have been slightly adjusted for this new navigation.
  - Keep in mind that it is a first step to the new User Experience we are working on, more to come.
- Duels
  - Matchmaking values have been tweaked for upcoming era, it now works as follow:
    - Has a floor of 1100 rating (if you have a lower rating, it will be considered as if you had 1100).
    - Widen at random interval the rating to match an opponent up 6 times, from +-50 to +-400.
    - If no opponent is found after ~150s, match someone randomly.
  - Added a SFX whenever you are matched as well as when you are running out of time in a game.
  - Coin toss weight is now based on your last 7 games (was 10 games before).
  - Music is now evolving during the game.
  - You can now disable emotes (globally in settings, during a game once the emote panel is opened).
  - Updated various VFX.
  - Added an option to show A/B/C/D & 1/2/3/4 landmarks on the cells header (useful for streaming or log reviews!).
  - Affinities added/removed are now shown on the card instead of in a toast.
  - Swap turn display has been updated.
  - Ending screen now shows you the reason for the victory/defeat.
- Cards
  - Combo card names now use "&" instead of "+" in their name.
- Profile
  - Match history is now available.
- Missions
  - Missions system has been revamped for the upcoming era. As such weekly missions have been reset, you can complete them one more time this week. If you had a pending daily/weekly chest before the maintenance, it was auto-claimed.
  - Some existing mission objectives have been updated.
- System
  - Performance of animation has been greatly improved on macOS and iOS.
  - Performance when displaying hundreds of items (such as cards in collections) have been greatly improved on all platforms.

### Fixes

- Duels
  - Fixed an issue preventing you from entering the matchmaking as well as canceling the queue.
  - Coin toss, preparation timer and default field are now correctly aligned.
  - Fixed legacy emote size.
  - Fixed various issues in log output.
- Missions
  - Fixed an issue where your first mission progress would not count toward the objective (first win, etc...).
- Profile
  - Avatar of the corresponding card is now correctly given on acquisition through crafting.

## 0.2.6d Hotfix 2

`2022-11-20 14:00 UTC`

### Changes

- Duels
  - AFK and Early Surrender leave penalty is now capped at 15 minutes and reset daily.
  - Coin toss bad luck protection now goes up to 90/10 odds from 75/25. Still based on yours and oppononent's last 10 games.

### Fixes

- Duels
  - Matchmaking rating first widening duration can no longer be wrongly reduced.

## 0.2.6d Hotfix 1

`2022-11-18 10:05 UTC`

### Fixes

- Duels
  - Duels are now ending correctly whether you surrender or are AFK.
    - Note: Stuck players will receive a compensation of +1000 Trisel. Players who played at least 1 match during the ~7 hours window in degraded conditions but were not stuck will also receive +300 Trisel.
    - Note: All matchmaking temporary bans (afk / early surrender) also have been lifted/reset.

## 0.2.6d Patch

`2022-11-18 03:00 UTC`

### Changes

- Duels
  - Logs now show you the card name and coordinates using A/B/C/D + 1/2/3/4 coords.
  - Custom options are now also shown at the top of the logs (for custom duels).

### Fixes

- Duels
  - Various fixes regarding player's timers and AFK timers.
- Cards
  - Updated rarities such as Honora & Hannibal card should now be correctly displayed.

## 0.2.6c Patch

`2022-11-17 16:00 UTC`

### Fixes

- Duels
  - You will now be redirected back to the dashboard if you encounter an error while queuing.
- Crafting
  - Trisel deduction after merging is now correctly displayed (was wrongly shown on the client before).

## 0.2.6b Patch

`2022-11-17 13:00 UTC`

### Fixes

- Crafting
  - Trisel cost for Merge is now correctly shown.

## 0.2.6 Patch

`2022-11-17 05:00 UTC`

### Changes

- Duels
  - Trisel and Exp gains have been adjusted to let you earn more under some circumstances:
    - You get more Trisel and EXP on your wins based on your rating. Thresholds are at 1150 / 1500 / 1850 / 2200 / 2550. For each threshold you have +5 Trisel / +50 EXP per win.
  - Matchmaking now has a floor rating of 1000. It means that every player below 1000 rating is considered at 1000 for matchmaking purpose.
    - Note: This change is mandatory in order to maintain the integrity of the economy as some users were purposely losing on their accounts in order to be matched against themselves in very low elo. Hundreds of thousands of Trisel has been earned that way.
    - We have temporarily banned those accounts and removed all EXP/Trisel gains, if the Trisel were already spent, the balance will be negative and they will have to earn back everything.
    - Keep in mind that we banned only accounts that abused the system, if you did encounter your other account only a few times you have not been banned. Keep in mind that this is still against the fairness rules and further measures might be taken against such behavior in the future.
  - Timeout and Surrender rules have been revisited as follow:
    - If you surrender before or during Turn 10, it is considered as an Early Surrender.
    - Games have a duration of 5mins although each turn has now a maximum duration of 2mins, if the player does not end his turn (by playing a battle card) during those 2mins, he will lose the game as it is considered being AFK.
    - Being AFK or making an early surrender triggers a matchmaking penalty that prevents you from queuing for a certain amount of time.
    - This time exponentially increases on each penalty. It is reset weekly.
    - Before making an early surrender, a window pop-up warns you about it.
    - After not playing the turn for 1 min, a 60s countdown appears below the player. If it reaches 0, the game is lost for the AFK player.
      - Note: Disconnects are not fully handled regarding this timer display on the client side, i.e. if you disconnect and reconnect late into a turn you might not see the countdown. This will be fixed in an upcoming update.
    - Surrendering after turn 10 (turn 11 and so on) will not trigger any penalty. Although keep in mind that for missions accomplishment, the win will count as if the opponent controlled 100% of the board.
  - Improved card glow VFX while in hand.
  - Improved card affinities VFX while on the board.
- Cards
  - Honora & Hannibal is now correctly displayed as Special Rare (was Rare before).
    - Note: NFT version will be changed after migration.
  - Hanzo & ValRed is now correctly displayed as Rare (was Uncommon before).
  - Nox & Skeleton is now correctly displayed as Ultra Rare (was Uncommon before).
  - Multiple metadata such as illustrator name have been updated.
    - Note: NFT version will be changed after migration.
- Loots
  - Reward, Daily and Weekly chests can now contain foil cards.
  - Pack progress is now shown if opening more than one pack.
- Crafting
  - Merge (to make Combo cards) will be enabled on `2022-11-17 17:00 UTC`.
- Shop
  - Neo Halloween chest will be removed from the Shop on `2022-11-17 17:00 UTC`.
- Profile
  - You can now redeem codes you received in your profile. Be aware that attempting to redeem invalid codes multiple times will ban you.

### Fixes

- Duels
  - No longer incorrectly reward an extra 20 Trisel on win if all unlocker slots were full.
    - Note: This was an old implementation before convert was added to the game, it has then be replaced by the convert and the rating bonus.
  - Emote selector layout has been fixed if using Legacy emote.
  - Correctly freeze the players timer when the last card has been played.
- Crafting
  - Correctly clear the card selector on tab change.
- Perks
  - Golden & Golden Legacy now correctly increase your CTA cap (+500 and +1000 respectively).
  - Last tier bar progress display is now correctly displayed.
- Dashboard
  - No longer show loading artifacts.
- Profile
  - Wallet ID and Immutascan Link are now correctly displayed.
  - Emote selection should now behave correctly.

### Notes

- Crafting wording will be updated as follow:
  - Potential Merge -> Power Up
  - Alternative Merge -> Merge
  - Alternative Combo -> Combo

## 0.2.5b Patch

`2022-11-09 20:45 UTC`

### Fixes

- Loots
  - Reward chest opening should no longer be stuck.

## 0.2.5 Patch

`2022-11-09 17:00 UTC`

### Changes

- Loots
  - Legacy packs are now available for opening, it will be enabled on 2022-11-09 @ 19:00 UTC.
  - Chest opening animation can now be skipped.
- Crafting
  - Awakening is now available, it will be enabled on 2022-11-10 @ 17:00 UTC.
- Cards
  - Free mint (if you have any) is now used instead of CTA Tokens.
- Missions
  - A new mission has been added, it requires you to unlock instead of open chests.

### Fixes

- Profile & Settings
  - Various fixes
- System
  - Game should now be able to connect to the internet on older versions of macOS.

## 0.2.4 Patch

`2022-11-05 10:00 UTC`

### Changes

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

### Fixes

- Duels
  - Player remaining time correctly shows what is set in Friendly Duel.
  - Foil effect is now correctly displayed on animated cards.
  - Foil effect is now correctly displayed on opponent cards.
- Missions
  - Login mission is now completed whenever you access the missions, you no longer have to relog.

## 0.2.3 Hotfix 1

`2022-11-01 23:30 UTC`

### Changes

- Missions
  - Added a new mission (both with daily and weekly objectives), its objective is related to the amount of cards captured during ranked duels.
  - Added 3 new weekly missions (total is now 24). Win and Capture X in a single turn T1 and T2 now rewards half completion %. It means you need to do at maximum 23 of the 24 missions available to unlock weekly T3. Also you now have +240 Trisel per week that way.
  - Update various objectives.

### Fixes

- Duels
  - Matchmaking conditions are now correctly checked for both players.
- Crafting
  - Field cards now correctly require 10 cards to be merged like other uncommon cards.
- Missions
  - Capture X in a single turn advancement now only shows you 0 / X until you complete it.

## 0.2.3 Patch

`2022-10-28 23:45 UTC`

### Fixes

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

### Changes

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

### Fixes

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

### Fixes

- Cards
  - Weekly rotation is now available for players who used rotation card as leader or with empty decks. Once you login, the rotation cards should be available. Note that since 0.2.1 patch, rotation cards are displayed only in card selection when building a deck not in the collection.

## 0.2.1 Patch

`2022-10-20 03:00 UTC`

### Changes

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

### Fixes

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

### Notes

- Following our [announcement](https://medium.com/cross-the-ages/cross-the-ages-tcg-early-access-game-updates-14e0742b5f9), Legacy packs and Missions are not yet available in this version.
- Launcher (to auto-update the game) is still being worked on.
- In an upcoming update, numbering will be split to separate foil and non-foils as well as each version of the minting passes. This will be done at the same time as we migrate from Stardust collection to Cross The Ages one on IMX.
- After the GA, C+ drop rate will be roughly halved.

## 0.2.0 Patch

`2022-10-12 16:30 UTC`

Initial release of the Early Access.
