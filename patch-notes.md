# Cross The Ages: TCG Open Beta Patch Notes

## Direct Links

- Upcoming
  - [Upcoming](#upcoming)
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

Changes

- Duels
  - You can now report your opponent's name.
  - Opponent card placement is now animated.
  - Persisting effects are now shown directly on the board.
  - Combo cards grade A or S will now show the cinematic of the character its arkhome is from.
  - Game window will now be put in foreground if you are in the queue and are matched.
- Cards
  - You can now purchase animation level 2 using your free animation or CTA Token otherwise.
- Loot
  - You now dynamically see how many chests left you need to unlock before getting slot #3.
- Crafting
  - You now have an "auto" button for power up. It will automatically consume eligible duplicate cards at 0 potential from highest to lowest numbering in order to reach the rank you set.

## 0.3.0.2492 Patch

`2022-12-10 17:30 UTC`

Changes

- System
  - Versioning now add build number instead of a letter as 4th argument.
  - Added a "Reset" button on the splash screen. Do not use it unless you have some issue with the game data, if you do it will close the game and re-download everything on next launch.

Fixes

- Dashboard
  - Game mode dropdown is now working again.
  - Missions is no longer shown as locked.
- Leaderboard
  - List is once again visible.
- System
  - Fixed an issue preventing some light to be added to effects.

## 0.3.0b Patch

`2022-12-10 09:30 UTC`

Changes

- Settings
  - Added an option to limit game's resources for low-end devices.
- System
  - Lowered some graphics requirements from the game.
  - Reworked the launch of the application in order to pre-load some needed assets as well as being more explicit of the tasks being done in the loading progress bar.
  - Various UI updates for small resolutions.

Fixes

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

Changes

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
  
Fixes

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

Notes

- This release also features mobile versions for OGs, Moderators and Testers.
- Keep in mind that there are multiple display issues and that we are not looking for feedback on those, we are ONLY looking for blocking issues such as crash / cannot start / blocked in a menu / etc...
- All the visual details are being polished for every resolution, no need to report them at this moment.

## 0.2.7c Patch

`2022-12-05 00:30 UTC`

Fixes

- System
  - Fixed an issue preventing launch on some devices.

## 0.2.7b Patch

`2022-12-04 23:30 UTC`

Fixes

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

Fixes

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

Changes

- Duels
  - AFK and Early Surrender leave penalty is now capped at 15 minutes and reset daily.
  - Coin toss bad luck protection now goes up to 90/10 odds from 75/25. Still based on yours and oppononent's last 10 games.

Fixes

- Duels
  - Matchmaking rating first widening duration can no longer be wrongly reduced.

## 0.2.6d Hotfix 1

`2022-11-18 10:05 UTC`

Fixes

- Duels
  - Duels are now ending correctly whether you surrender or are AFK.
    - Note: Stuck players will receive a compensation of +1000 Trisel. Players who played at least 1 match during the ~7 hours window in degraded conditions but were not stuck will also receive +300 Trisel.
    - Note: All matchmaking temporary bans (afk / early surrender) also have been lifted/reset.

## 0.2.6d Patch

`2022-11-18 03:00 UTC`

Changes

- Duels
  - Logs now show you the card name and coordinates using A/B/C/D + 1/2/3/4 coords.
  - Custom options are now also shown at the top of the logs (for custom duels).

Fixes

- Duels
  - Various fixes regarding player's timers and AFK timers.
- Cards
  - Updated rarities such as Honora & Hannibal card should now be correctly displayed.

## 0.2.6c Patch

`2022-11-17 16:00 UTC`

Fixes

- Duels
  - You will now be redirected back to the dashboard if you encounter an error while queuing.
- Crafting
  - Trisel deduction after merging is now correctly displayed (was wrongly shown on the client before).

## 0.2.6b Patch

`2022-11-17 13:00 UTC`

Fixes

- Crafting
  - Trisel cost for Merge is now correctly shown.

## 0.2.6 Patch

`2022-11-17 05:00 UTC`

Changes

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

Fixes

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

Notes

- Crafting wording will be updated as follow:
  - Potential Merge -> Power Up
  - Alternative Merge -> Merge
  - Alternative Combo -> Combo

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
