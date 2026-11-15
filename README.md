# Sm64coopdx Chaos Mod
[GTA V Chaos mod](https://www.gta5-mods.com/scripts/chaos-mod-v) to Super Mario 64

**THIS MOD IS FOR SINGLEPLAYER ONLY, MULTIPLE PLAYER IS UNTESTED AND REALLY BUGGY**

## What?
- [How does it work?](#How-does-it-work)
- [Installation](#Installation)
- [Settings](#Settings)
- [Twitch integration](#Twitch-Integration)
- [Event list](#All-the-events)
- [Informations](#Information)
- [To-do list](#TO-DO)

## How does it work?
It's easy, every X secondes (changable in the settings) a random event can happen. The event could be instant or be timed

D-pad Left: Enable the mod
D-pad Right: Disable the mod

## Installation
1. Download the [latest release](https://github.com/SamLeGamerYB/Sm64coopdx-Chaos-Mod/releases/latest).
2. Unzip it and place the folder in ``[SM64COOPDX]\mods``
Should be looking like this:
```
sm64coopdx.exe
coopdx_updater.exe            /- main.lua
mods -------- TwitchChaosMod <
discord_game_sdk.dll          \- readme.txt
lang
palettes
dynos
coop.map
```
3. Launch the game and activate the mod
4. When you are in a save with 0 stars and you read the warrning you can say "/ireadit" the the chat (default keybind: enter)

## Settings
- You can toggle between "Offline Mod" (Random even every X seconds) or "Twitch Chaos" (Let people in the chat vote (By saying the number next to the event name) for the next event.)
- Speedrun, Enable a timer. (Please take notes that could be on Speedrun.com)
- Twitch Username (If empty, the mod will automaticly put Offline mod)
- Timer between events
- Length of the events
- All events can be toggled (**!! One with the "*" mean this could cause an epileptic seizure!!**)

## Twitch Integration

### What does it do?
It's letting people from the Twitch chat saying numbers between 1 to 4 and then 5 to 8 to affect the effect. The number of the effect wanted is shown on the HUD.

### How to use Twitch Integration?
Easy
1. first install the mod ([Instruction here](#Installation))
2. Go into the [settings](#Settings) and put Twitch Chaos
3. In "Twitch Username" Put your twitch username. Example: twitch.tv/**samlegamergd** --> "samlegamergd"
4. Close the menu and play the game!

## All the events
```
- Invisible Mario (Makes the player Invisible
- Reverse Control (Reverse all stick movement)
- Low Gravity (Player will be in low gravity)
- Big Mario (Makes the player 2x his size, hitbox are affected too)
- Tiny Mario (Makes the player 0.5x his size, hitbox are affected too)
- Random Teleport (Makes the player teleport in a random location) [1 TP]
- Kill streak (The player need to kill any mob under 10 seconds until the event ends)
- No-hit (The player have one HP and can not heal back until the timer end)
- Immortality (makes the player immunes to any damage, things that one-shot you keeps killing you)
- Swimming (Makes Mario swim in the air, the oxygene meter is present)
- Ad-break! (Makes an ad about my youtube channel at the bottom of the screen)
- Bad Apple (Makes the game black and white)
- *Random (Makes the game's textures and music completly random)
- 2x More Chaos (Makes the chaos coming two times faster)
- What is happening? (Makes all the actives effects invisible)
- -1 star (Makes a collected star go back to this original place
- +1 star (Makes the player collecting one random star from any level)
- High Gravity (Player will be in high gravity)
- Ice Physics (Makes all the floor slipery, like ice)
- Super Speed (Player will be faster)
- Snail (Player will move slower)
- /tp ~ ~100 ~ (Player will be teleported high in the sky)
- Random Gravity (Makes the gravity's direction changes temporarly)
- Suicide (Player dies)
- I see you (Makes every hostile mob targeting you and want you dead)
- *4K (Makes the quality game horrible
- Longer events (Makes the events last two times longer)
- Water VS Lava (Makes the lava and water change position)
- Random Imputs (Make every imputs randomize)
- Lag (Making the game having Roll-back)
- Kifflom! (Makes every sound effect "Kifflom")
- Mute (Makes the game's music stop)
- Fake Random Teleport (Execute the "Random Teleport" effect, except that you will go back where you were [2 TP]
- Fake Fake Random teleport (Execute the "Fake Random teleport" effect, except that you will go back where you were [3 TP]
- First Person (Makes the player's camera into Mario's head)
```
\* = Could cause epileptic seizure
## Information
I don't know how to code so this mod has been created by ChatGPT (Sorry)
Windows (Windows 9, Windows 10 and Windows 11) only so far

## TO-DO

- [x] Twitch voting system
- [x] Seizure warrning
- [ ] Speedrun.com Category
