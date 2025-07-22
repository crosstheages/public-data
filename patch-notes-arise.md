# Cross The Ages: Arise Patch Notes

## Direct Links

- 0.1
  - [0.1.0.21](#01021-patch)
  - [0.1.0.20](#01020-patch)
  - [0.1.0.19](#01019-patch)
  - [0.1.0.4](#0104-patch)
  - [0.1.0.3](#0103-patch)
  - [0.1.0.2](#0102-patch)
  - [0.1.0.1](#0101-patch)
  - [0.1.0.0](#0100-closed-playtest)

## 0.1.0.21

`2025-07-23 16:00 UTC`

### Fixes
- Light Ability 2 and Ultimate is now adding the aura correctly on players
- Sound settings is now correctly applied on the start of the application

### Known issues
- Sprint does not work on Land when using a gamepad
- Fireball (Ability 2 of the Fire weapon) may fail to spawn if it collides too closely with the environment
- AMD RX57.. GPUs fail to render most dungeon textures
- Character animations for Samia, Takeshi, and Ellie may fail to load properly in gravitational flux zones
- Manual lock-on targeting is currently disabled on gamepad due to technical issues
- Your character can be sometimes teleported to the boss platform during the QTE without being immune (you could be vulnerable due to creature snapping if you are in combat with)
- Sometimes, the key show on the first step of the tutorial is shown as QWERTY keyboard (so Z even if you are on AZERTY keyboard so W)
- Cooldown could have some problems of visibility if you have a action modifier from talents
- Light Ability 2 and Ultimate can sometimes not apply the aure correctly on players if talent modifiers is activated 

### Tips
- Note that if you have any problems of "data syncrhonization", you can fix it by restarting the game
- If you occur GPU crash, you can modify the quality settings in the main menu and lower it
- The automatic benchmark at launch may select overly demanding settings, manually adjust graphics options if experiencing low FPS

## 0.1.0.20 patch 

`2025-07-23 12:00 UTC`

### Fixes
- Fixed Combo 2 and Ability 2 damages of the Water
- The talent preview in the talent menu does not display correctly when using a mix of elements (this does not affect in-game behavior)

## 0.1.0.19 patch 

`2025-07-23 08:00 UTC`

This playtest is only available from Epic Games for Windows Platform. 
Note that Easy Anti-Cheat is now active and required to play Arise

### Content
- You can play using a keyboard and mouse or an Xbox gamepad (PlayStation controllers and other types are not currently supported)
- A feature to reduce the key is now available from the Artellium map
- One dungeon is available for this Closed Playtest: CERAK Cave
- Matchmaking has been disabled during this phase
- Jump gravity has been adjusted (a full update of jump mechanics will come in the next stage)
- Dialogues are now locked to a single sequence in competitive mode (full dialogues still available in tutorial mode)
- Light weapons have been added, along with their talent trees
- Life weapons have been added, along with their talent trees
- Water weapons have been added, along with their talent trees
- Earth weapons have been added, along with their talent trees
- Crystals can now drop Light, Life, Water and Earth weapons
- Dungeon difficulty ramp has been increased by about 80%, and crystal drop rates have been adjusted accordingly to match Closed Playtest 1 difficulty levels
- The health multiplier for creatures has been adjusted to +80% per player (was +100% in the previous playtest)
- Two "Top 200 World" leaderboards are now available: one filtered by MOCA members, the other by CTA members
- Three additional playable characters have been added (they are only visuals characters, no impact on the gameplay. In this Closed Playtest, you will be to create only one character and not able to change after creation)
- A snapping feature has been added: creatures that lose line-of-sight or are too far from their target will now teleport to it if they are still in combat
- Player names and group member locations are now visible above characters inside dungeons
- Two server regions are now available. Players from different regions will share leaderboards and can group together. However, the dungeon instance will launch in the region of the key owner
- An access code is now required to connect to the game
- New elite loot drops have been added to the map
- Weapon selection using a gamepad has been improved
- Gravitational flux speed has been increased
- The Land and Dungeon HUDs have been reworked
- If disconnected during a dungeon, players can now reconnect to the same instance

### Fixes
- Fixed lighting and collision issues in Dungeon 1 and improved some visual elements
- The talents menu now correctly displays the selected character
- Sprint, and dash are now functional on Land
- If you exit or forfeit a dungeon as the leader, you will now lose one key level
- Fixed differents issues on social, UI, etc...
- Fixed issues related to unit frame updates when dealing damage.

### Known issues
- Sprint does not work on Land when using a gamepad
- The talent preview in the talent menu does not display correctly when using a mix of elements (this does not affect in-game behavior)
- Combo 2 and Ability 2 of the Water weapon sometimes deal no damage on the Shipping build
- Fireball (Ability 2 of the Fire weapon) may fail to spawn if it collides too closely with the environment
- AMD RX57.. GPUs fail to render most dungeon textures
- The automatic benchmark at launch may select overly demanding settings, manually adjust graphics options if experiencing low FPS
- Character animations for Samia, Takeshi, and Ellie may fail to load properly in gravitational flux zones
- Manual lock-on targeting is currently disabled on gamepad due to technical issues
- Your character can be sometimes teleported to the boss platform during the QTE without being immune (you could be vulnerable due to creature snapping if you are in combat with)
- Sometimes, the key show on the first step of the tutorial is shown as QWERTY keyboard (so Z even if you are on AZERTY keyboard so W)
- Light Ability 2 and Ultimate is sometimes not adding the aura correctly on players
- Cooldown could have some problems of visibility if you have a action modifier from talents

### Tips
- Note that if you have any problems of "data syncrhonization", you can fix it by restarting the game
- If you occur GPU crash, you can modify the quality settings in the main menu and lower it
- The automatic benchmark at launch may select overly demanding settings, manually adjust graphics options if experiencing low FPS

## 0.1.0.4 patch 

`2025-05-30 12:00 UTC`

### Fixes
- Removed collisions on some Fog in "CERAK Cave"
- Fixed a crash server that could happen sometimes when damaging an "invalid" characters
- Added a visible ping during 1s on yourself when you are pinging on yourself
- Fixed the details of the Weapon in the Inventory Chest
- Fixed the strengths and the weaknesses of Heptagram inside the CharacterCreation
- Fixed aura names in the talent tree
- Damages of the Triple Tail Attack is now scaling with the dungeon level
- Improved the collision of the rail inside the Laboratory
- Fixed the position of some creatures that were spawning under map inside the tunnels
- The first break of the bridge is now sync on the start of the dungeon to be always accurate on the timer
- Rotations of sphere and Hand in the Room 1 are now sync on the start of the dungeon to be always accurate on the timer
- Improved the path to access to the Hand in the Room 1
- Increased the speed of the Gravitational Flux to go to Pietro Room and come back too
- Fixed an issue where players could be visible on the boss platform during the QTE and not immune to damage
- Fixed an issue where a player could be blocked when trying to connect to server after renaming its Epic account username (after a first connection on the previous one), players can connect to the game
- Fixed an issue on the matchmaking where a player could be stuck and get the error on game allocation when trying to start a game. After this update, players in this case need to log in, log out and log in again to fix it.
- World rankings is now capped to 200 records

### Known issues
- Sprint is deactivated when moving the character laterally.
- Sprint toggle on controller turns off after performing a dash.
- Sprint does not activate when landing.
- Malik's beard may occasionally appear misaligned.
- The informations of the player on the HUD are not correctly updated
- The key information on the top right inside the the artellium map is not always correctly refreshed
- The Elite can sometimes jump through walls if the player is in other room and not visible by the AI
- Only XBox Gamepad controller is supported
- Some desync/visual bugs can occur visually if a player is far from others when interaction in "CERAK Cave"

## 0.1.0.3 patch 

`2025-05-29 12:00 UTC`

### Content
- Updated the cinematic 2.5D video
- Updated the main menu video

### Fixes
- Fixed the issue where the player could be blocked during some tutorial steps
- Fixed the issue where the player could be blocked by spamming Interaction key during the dialogue of the refugees
- Fixed the issue where you were able to spam interaction key
- Fixed the camera that was blocked when leaving the talent building
- Fixed "On the step "Select weapon" of the tutorial, on Azerty keyboard, the key can be visible as "Z" but it's "W""
- Fixed "The crystal building widget appears as "Placeholder""

### Known issues
- Sprint is deactivated when moving the character laterally.
- Sprint toggle on controller turns off after performing a dash.
- Sprint does not activate when landing.
- Malik's beard may occasionally appear misaligned.
- In multiplayer, other players can be visible during the QTE on the boss platform and can be damaged!
- The informations of the player on the HUD are not correctly updated
- The key information on the top right inside the the artellium map is not always correctly refreshed
- The Elite can sometimes jump through walls if the player is in other room and not visible by the AI
- Only XBox Gamepad controller is supported
- Some desync/visual bugs can occur visually if a player is far from others when interacted
- If a player reanme its Epic account username after a first connection on the previous one, he will be blocked when trying to connect to server

## 0.1.0.2 patch

`2025-05-28 12:00 UTC`

### Fixes
- Fixed the login issues for external organization players

### Known issues
- Sprint is deactivated when moving the character laterally.
- Sprint toggle on controller turns off after performing a dash.
- Sprint does not activate when landing.
- Malik's beard may occasionally appear misaligned.
- In multiplayer, other players can be visibile during the QTE on the boss platform
- The informations of the player on the HUD are not correctly updated
- The key information on the top right inside the the artellium map is not always correctly refreshed
- The Elite can sometimes jump through walls if the player is in other room and not visibile by the AI
- When leaving the talent tree building, camera can be stuck in body (To fix it: opening main menu resets the camera)
- When you are at the Tutorial step "Combo", all controlled can be stuck
- Only XBox Gamepad controller is supported
- On the step "Select weapon" of the tutorial, on Azerty keyboard, the key can be visible as "Z" but it's "W"
- The crystal building widget appears as "Placeholder"
- Player can be stuck in the dialogue of the refugees when spamming Interact after the object has been obtained

## 0.1.0.1 patch

`2025-05-27 08:00 UTC`

### Changes
- Added the building for the talent tree
- Made some optimizations on the social menu, talent tree and size levels loading
- Updated the introduction video of the dungeon 1

### Fixes
- Fixed issues on some colliders
- Fixed an issue where the boss music where not played in some cases (during multiplayer game)
- Fixed some translations on the ping messages
- Fixed an issue on the cam position of the LevelSequence of the Refugees
- Fixed an issue where it was possible to stuck the camera on the body character when leaving the options menu
- Fixed the blank images of the Elite buff
- Fixed some talents that was not correctly applied at the spawn of the character
- Fixed some issues with the ping system

### Known issues
- Sprint is deactivated when moving the character laterally.
- Sprint toggle on controller turns off after performing a dash.
- Sprint does not activate when landing.
- Malik's beard may occasionally appear misaligned.
- In multiplayer, other players can be visibile during the QTE on the boss platform
- The informations of the player on the HUD are not correctly updated
- The key information on the top right inside the the artellium map is not always correctly refreshed
- The Elite can sometimes jump through walls if the player is in other room and not visibile by the AI
- When leaving the talent tree building, camera can be stuck in body (To fix it: opening main menu resets the camera)
- When you are at the Tutorial step "Combo", all controlled can be stuck
- Only XBox Gamepad controller is supported
- On the step "Select weapon" of the tutorial, on Azerty keyboard, the key can be visible as "Z" but it's "W"
- The crystal building widget appears as "Placeholder"
- Player can be stuck in the dialogue of the refugees when spamming Interact after the object has been obtained


## 0.1.0.0 Closed Playtest

`2025-05-14 08:00 UTC`

### Content & Gameplay Loop

https://www.crosstheages.com/fr-fr/news/cta/arise-closed-playtest-1/

