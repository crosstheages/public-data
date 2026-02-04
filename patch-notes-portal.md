# Cross The Ages: Portal Patch Notes

## Direct Links

- 0.1
  - [0.1.1](#011-crafting)
  
- 0.2
    - [0.2.5](#025-brick-breaker-account-deletion-and-migration-updates)
    - [0.2.4](#024-wheel-update-and-briges)
    - [0.2.3](#023-mystery-box-and-dashboard-updates)
    - [0.2.2](#022-em)
    - [0.2.1](#021-defi)
    - [0.2.0](#020-solana)


## 0.2.5 Orb Digger, Account Deletion and Migration Updates
`2026-02-XX`

### New Features

- **Shop - Orb Digger Mini-Game**
    - New arcade-style mini-game now available in rotation
    - Weekly rotation schedule: Mystery Box → Wheel → Orb Digger
    - Available at: https://portal.crosstheages.com/shop/miner

- **Account Management - Account Deletion**
    - Users can now permanently delete their CTA account from My Info settings
    - **Two deletion scenarios:**
        - **New accounts (no assets):** Immediate deletion with instant username and authentication method release
        - **Accounts with assets:** 30-day grace period with immediate deactivation
    - **Asset handling:**
        - Web3 assets (NFTs, tokens) remain in your Solana wallet
        - Web2 assets (in-game items, virtual currency) permanently deleted after 30 days
    - **Cancellation:** Deletion can be cancelled within 30 days by reconnecting to the portal
    - Email notifications sent at confirmation, 7 days before final deletion, and upon completion

### Important Updates

- **IMX → zkEVM Migration - Critical Changes** 🚨
    - **Automatic CTA token migration has ENDED**
    - All remaining CTA tokens must now be migrated **MANUALLY**
    - **Migration paths based on your situation:**
        - ✅ **Already fully migrated:** No action needed
        - ⚠️ **Nothing migrated yet:**
            1. Retrieve seed phrases at end of migration process
            2. Import into MetaMask
            3. Bridge manually: IMX zkEVM → ETH via https://toolkit.immutable.com/ethereum-bridge/
            4. Then ETH → Solana via https://portal.crosstheages.com/bridge/bridge-tokens
        - 🔍 **Found MetaMask wallet with CTA tokens or NFTs:**
            - NFTs: Verify and bridge at https://portal.crosstheages.com/bridge/bridge-s01-assets
            - Tokens (on zkEVM): Bridge manually IMX zkEVM → ETH → Solana
    - **Note:** NFTs and Web2 assets are NOT impacted by token migration changes
    - **Support:** https://crosstheages.atlassian.net/servicedesk/customer/portal/2/group/6/create/93



## 0.2.4 Wheel Update and Bridges
`2026-01-07`

### New Features
- Bridge (https://portal.crosstheages.com/bridge)
    - Only available on PC, the bridge requires Metamask (for IMX and Polygon) and Phantom for asset reception
    - The bridge is open access, you don't need to be logged in to bridge assets to any Solana address of your choice
    - From the same interface, you can bridge IMX → SOL or POLYGON → SOL
    - For the bridge to work properly, you must have POL on Polygon and SOL on the Solana address

### Updates
- Shop
    - Wheel update with new design to match the Mystery Box aesthetic


## 0.2.3 Mystery Box and Dashboard Updates

`2025-12-10`

### New Features

- Shop
    - Launch of new Mystery Box for VIP progression and orb rewards
    - New chances and new prizes available
    - Grand prize: 575,000 Orbs
    - Available at: https://portal.crosstheages.com/shop/mystery-box

### Improvements

Following feedback from the Portal test team:

- Dashboard
    - Added shortcut to staking from CTALS section
    - EM now displayed directly on Dashboard
    - Added expiration dates for orbs in Dashboard tooltips

- Inventory
    - Physical Collection: Highest numbering now selected by default when claiming

### Coming Soon

- Bridge Polygon → SOL
- Bridge IMX → SOL



## 0.2.2 EM

`2025-11-19 08:00 UTC`

### Changes

- Home
    - Display and redirect to corresponding pools for CTA TOKEN / CTASTO / CTATRI / CTALS
    - Display and redirect to official CTA pools: SOL/CTA - CTATRI/CTA - CTASTO/CTA - CTALS/CTA - BORG/CTA

- Inventory - Assets:
    - Enabled MINT for static cards from the Blockchain State filter: STATIC - S4
- Inventory - Binders: EM (Eternal Multiplier) Implementation:
    - Display of your current Eternal Multiplier
    - Display of your attainable Eternal Multiplier
    - Display of your gain ratio based on 100 Ark earned in Blast
    - Display of progress bars: Total EP on account vs Total Activated EP
    - Display of 5 binders, limited to avoid page overload
    - How the Total EP on Account bar works:
        - All ETERNAL/PHYSICAL cards count toward the Total EP on account calculation
    - How the Total Activated EP bar works - there are 3 ways to increase your activation bar:
        - Activating 1 EP requires a value of $0.04
        - Mint Passes count as dollar value, this value is calculated on a 7-day average. If you purchase a Mint Pass, it will take 7 days to reach its full potential with a daily increase of 1/7 until day 7. Here is the $ value per Mint Pass:
            - Red Mint Pass: $70
            - Green Mint Pass: $140
            - Blue Mint Pass: $280
            - Legacy Mint Pass: $490
            - Golden Mint Pass: $1,470
            - Golden Legacy Mint Pass: $5,390
        - The 7-day rolling average $ value of CTALS held in the account
            - Physical cards now always secure one third of the EP they contribute by raising the EM cap accordingly. Along with the permanent 3x EP bonus they grant in any season, each EP from a physical card also adds about $0.015 to the EM cap. This adjustment ensures the 3x bonus has real value, guarantees at least a 1x contribution, and prevents situations where players claim a physical card but still end up with zero EM. The logic matches how Mint Pass works but applies individually to every physical card. For reference, a Maa grade C non-foil physical card lifts the EM cap by roughly $87.50, which is an increase of about x0.03 on the cap. Players can still reach the full benefit of the permanent 3x EP bonus by holding CTALS and/or Mint Pass.




## 0.2.1 Defi

`2025-10-29 08:00 UTC`

### Changes

- Dashboard
    - Overview:
        - Added on-chain Trisel / Stones and CTALS
        - Access to VIP and LEVEL display
        - VAULT CTA update: 
            - Added off-chain Trisel and Stones currencies with deposit and withdraw shortcuts
            - Added Orbs with shortcuts to the shop
    - VIP:
        - Added VIP tiers
        - Added progress status for orb collection and CTA token spending before next level
    - Rewards:
        - Display of orbs of echo collected during the week and how they were obtained
        - Display of Orbs of sealing generated per day, with tutorial explanation
        - CTALS staking shortcut
        - Shortcut to shop (shop opening on 11/05/25)
        - Shortcut to inventory
    - My Infos:
        - Username change option enabled
        - Email change option enabled
            - New email address verification system
        - Option to display or hide username publicly when marketplace opens. Disabled by default
    - Staking:
        - Manage your staking
        - Check your CTALS and CTA token balance
        - View total value locked in the ecosystem (chart coming soon)
        - Ability to stake/unstake
        - Table to track and claim your ongoing unstaking

- Inventory
    - Assets Section: Launch of inventory on Solana
        - Added Eternal/Flex (for ErikaS2) /Static S4 / Physical
    - Physical Section:
        - Ability to convert your Eternal cards to Physical status
        - View collections you've converted to Physical
        - Order summary with Recovery Code that will allow you to access the "Physical collectible cards" product at the HL event (for free) or early 2026 on Shopify.
    - Enabled MINT for static cards

- Shop
    - VIP wheel activation
    - Preparation for opening on 11/05/25 for purchases with orbs of sealing and orbs of echo

- Bridge
    - Fixed a bug that prevented withdrawal of CTA tokens on Solana after a bridge

## 0.2.0 Solana

`2025-09-29 08:00 UTC`

### Changes

- Dashboard
    - Overview:
        - UX update for the delegate
        - Added a manual mint button after your migration in the CTA vault section to retrieve your NFTs on Solana
        - Added the ability to KYC a new account not originating from a migration

- Inventory
    - Assets Section: Launch of the inventory on Solana
        - Added Eternal/Flex S3/Static S4 filters
    - Products Section: Launch of the product switch
        - Management of mass shredding by product
        - Added the ability to craft a product
        - Display of the number of copies of the same product
        - Added the owned filter
    - Binders Section:
        - Launch of the first EP binder
        - Note: The displayed EPs are incorrect; there is a discrepancy due to the postponement of the S3 Rift mint
        - Added grayed-out cards in the background for cards I do not own
        - Ability to craft a card from the binders

- Limited Time Offer
    - Launch of the LTO until October 22, 2025, 8 AM UTC

- Shop
    - Shop activation
    - Ability to purchase an ETERNAL S4 pack at full price for users without a mint pass

- Bridge
    - Activation of the CTA token bridge ETH<-->SOL

## 0.1.1 Crafting

`2025-04-17 08:00 UTC`

### Changes

- Crafting
    - Accessing the Craft :
        - Crafting is exclusively available through the CTA Wallet. If your cards are on the custom wallet, make sure to transfer them to the CTA Wallet beforehand. Head to the Product section to get started. This section will soon evolve into a central hub for managing your assets post-migration. [PRODUCTS](https://portal.crosstheages.com/market/cards/products) You’ll also find the craft feature in the section dedicated to the Eternal Multiplier.
        - Good to Know Before Crafting
        - IMX Processing Time: The process might take a little while. Avoid refreshing the page to prevent interrupting the craft or missing the animation.


    - Card Selection and Management :
        - Choose the minimum quality (foil or non-foil) and the minimum grade for your merges.
        - Compatible cards are selected automatically. If a card exceeds the minimum grade (e.g., Grade A for a minimum of C), you’ll need to select it manually to avoid mistakes.
        - NFT R1 cards are included by default.
        - Quick Purchase: Need a card? Buy it directly at the floor price via the craft pop-up using CTA tokens or USDC.
        - Crafting Alternatives: From a merge, you can now redirect to crafting an alternative (an upgrade to craft without leaving the merge.
        - Visible Results: At the end of the craft, check the card’s current floor price and the crafter’s username displayed on it.

    - Share Your Creations!
        - Show off your crafts to the community and the world via social media!


    - Search:
        - The search system has been completely overhauled to make finding specific cards easier. The search refines results as you type in the search bar.
        - Note: Card names must be entered in the language selected on the portal.

### Fixes

- Search:
    - The name sorting system has been reimplemented. Sorting options are now displayed directly with clear descriptions, removing the need for arrow-based navigation. :
    - Instead of "Sort by name" with an up/down arrow, you now have: 
        - Name (A → Z)
        - Name (Z → A)
