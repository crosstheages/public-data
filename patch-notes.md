# Cross The Ages: TCG Open Beta Patch Notes

## Direct Links

- 0.1.18
  - [Patch](#0118-patch)
- 0.1.17
  - [Hotfix 1](#0117-hotfix-1)
  - [Patch](#0117-patch)
- 0.1.16
  - [Hotfix 2](#0116-hotfix-2)
  - [Hotfix 1](#0116-hotfix-1)
  - [Patch](#0116-patch)

## 0.1.18 Patch

`2022-09-29 04:00 UTC`

This is a Release Candidate version, meaning this section will be updated on each iteration until the patch is out.  
Also if you encounter any issue, feel free to use the latest stable version by downloading from our website.

### RC 1

This RC is meant to fix most of the issues you can face during a game, mostly related to Reconnection or Touchpad devices.  
We are looking for detailed reports with logs if you still encounter those with this version, if so please report it as issue on our public tracker.

Changes

- Duels
  - Added a backdrop behind the player name & avatar to more easily read the name.

Fixes

- Launch
  - Fixed the launch button not appearing once reaching 100% of the progress bar.
- Duels
  - Fixed multiple issues during the reconnection.
  - Card effects are now correctly translated.
- Leaderboard
  - Correctly display each player avatar & avatar frame.
  - Scroll fetching fixes.

## 0.1.17 Hotfix 1

`2022-09-28 05:00 UTC`

Fixes

- Duels
  - Do correctly update players time left on timeout (more than 5 minutes elapsed for one of the players). Previously when the timer was about to hit 0, we would send the time from previous turn making a timeout ending screen with non-0 time left values which was confusing. Now, we display it correctly as 0.
- System
  - We made several changes to our North America and Asia datacenters in order to improve the reliability of the connection. We are still doing changes in collaboration with our partner but it should already be way more stable with less disconnect.

## 0.1.17 Patch

`2022-09-27 12:00 UTC`

Changes

- Duels
  - Matchmaking queue has been changed to favor opponent with close rating, you will be more often matched against opponent with close rating although queue time has a priority on this parameter. Also, the queue has been changed to be less predictable.
  - Arkhome backgrounds behind player name in the header have been updated.
  - Leader images in the header have been updated.
  - Added a button to go to the decks from the deck selection.
- Cards
  - Deck costs of alternative field cards have been corrected. If your deck is now above the deck power limit you must update it. Previously cost was a fixed 440 while it should have ranged between 440 and 500 depending on the grade.

Fixes

- Duels
  - Players time left at the end of the match (last turn) are re-synchronized. Keep in mind that depending on your setup the timers might be a little bit off compared to the server, we are currently exploring ways to improve the synchronization through the game.
  - Whenever a match has been ended by the server, you should now correctly see the victory/defeat screen instead of waiting with the timer at 00:00.
  - Fixed an issue showing the result from previous game instead of the current game.
  - No longer show cards from the previous reconnection on a fresh game.
  - Adjusted the draw area to be accessible in all resolutions.
  - Correctly display player rating during deck selection.
  - Correctly display opponent rating on versus screen.
- Cards
  - Fixed layout display of Special Attacks.
  - Last row of cards is now fully visible.
  - Invalid deck icon is now bigger.
  - Deck list is now correctly updated once deck is saved.
- Leaderboard
  - You can now more easily scroll others rank.
  - Order should no longer be mixed.
- Profile
  - No longer ask to save settings if not needed.
  - Enable full screen checkbox only if the layout is landscape.
  - Win rate % is now correctly displayed.
- Login
  - Updated password indications on sign-up form.
  - No longer show incorrect maintenance message.

## 0.1.16 Hotfix 2

`2022-09-24 12:15 UTC`

Fixes

- Cards
  - Updated Special Attacks name and description.  
    Note: An upcoming update will fix the layout issue.

## 0.1.16 Hotfix 1

`2022-09-23 21:30 UTC`

Changes

- Cards
  - Decks with less than 20 cards are no longer valid, if you made such a deck it is now flagged as invalid.
  - As a result of the previous changes, a new era has started meaning all stats from the ladder have been reset.

Fixes

- Login
  - Emails are no longer case sensitive.
  - You can now use the forgot password link to activate your account at the same time of resetting your password in case the activation link expired.

## 0.1.16 Patch

`2022-09-23 17:00 UTC`

Initial release.
