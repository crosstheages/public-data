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

`2022-10-06 10:00 UTC`

Changes

- Login
  - Updated the mails received on sign-up and on forgot password.
  - Links no longer expire on each request, you can re-use the same link as long as it was not previously used (in case you made 3 forgot password requests for example).
- Duels
  - Added a backdrop behind the player's name & avatar to more easily read the name.
  - Card invocations are now done only if the card is A or S grade.
  - Update the tiles color of the default field.
  - Game will now attempt to recover automatically the connection, in case it is not recoverable you will see a message telling you are disconnected.
- Cards
  - Import/Export strings have been updated to include the Special Attack (SA).
    - Note: You need to update your export strings, previous strings are no longer compatible!
- Profile
  - You can now open the profile & settings menu using "ESC" key while on the dashboard.
- Leaderboard
  - You can now go to your position by clicking on your rating on the top right.

Fixes

- Launch
  - Fixed the launch button not appearing once reaching 100% of the progress bar.
- Login
  - Login is now case insensitive.
- Duels
  - Power Stacking SA now works starting from the first turn.
  - Fixed a display issue showing attack attempt VFX under some cards.
  - Fixed an issue preventing the duel to show up as ended whenever you were matched with someone from another region (example: EU vs NA).
  - Fixed an issue wrongly showing you were disconnected.
  - You can now use the reconnection if you do login again (on the same device or another).
  - Fixed an issue where the board was empty when you did reconnect.
  - Fixed an issue regarding the cards you had after a reconnect if you did discard and draw before being disconnected.
  - Fixed issues related to touch devices such as touchpad, cards should no longer be blocked during a drag for example.
    - Note: We did a complete overhaul of our hand system logic, please do not hesitate to fill a report on our tracker if you encounter some issues in this regard.
  - You will no longer accidently open the card details using a long click while dragging a card.
  - Card glow is now correctly removed once a card is played.
  - Card effects on card details are now correctly translated.
- Profile
  - Audio settings are now correctly taken in account on restart.
  - Your avatar is now correctly displayed after changing it without restarting the game.
- Leaderboard
  - Correctly display each player avatar & avatar frame.
  - Scrolling has been smoothed.
- Social
  - You can now correctly exit a lobby while you are selecting a deck.
- Localization
  - Updated various text.

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
