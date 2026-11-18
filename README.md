# Sm64coopdx Chaos Mod
[GTA V Chaos mod](https://www.gta5-mods.com/scripts/chaos-mod-v) to Super Mario 64

**THIS MOD IS MEANT FOR SINGLEPLAYER ONLY, MULTIPLAYERS ARE UNTESTED AND REALLY BUGGY**

**Installing this mod will modifiy the gamefiles to have access to websocket** (This will do nothing for you execpt helping other modders)

[![Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/N6C026X3OU)

## What?
- [How does it work?](#How-does-it-work)
- [Installation](#Installation)
- [Settings](#Settings)
- [Twitch integration](#Twitch-Integration)
- [Event list](#All-the-events)
- [Information](#Information)
- [To-do list](#TO-DO)

## How does it work?
It's easy, every X seconds (changeable in the settings), a random event can happen. The event could be instant or timed.

D-pad Left: Enable the mod

D-pad Right: Disable the mod

## Installation
1. Download the [latest release](https://github.com/SamLeGamerYB/Sm64coopdx-Chaos-Mod/releases/latest) of the mod
2. Download the [SM64COOPDX Web port](https://github.com/SamLeGamerYB/sm64coopdx-https)
3. Unzip them and place them in the folder ``[SM64COOPDX]`` (Root of the .exe)
It should look like this:
```
sm64coopdx.exe
coopdx_updater.exe            /- main.lua
mods -------- TwitchChaosMod <
discord_game_sdk.dll          \- readme.txt
lang                           \-Audio
palettes
dynos
coop.map
```
3. Launch the game and activate the mod
4. When you are in a save with 0 stars and you read the warning, you can say "/ireadit" in the chat (default keybind: enter)

## Settings
- You can toggle between "Offline Mod" (Random event every X seconds) or "Twitch Chaos" (Let people in the chat vote (by saying the numbers) for the next event.
- Use OAuth (To log-in with [Twitch](https://twitch.tv/)
- Timer between events
- Length of the events
- All events can be toggled (**!! Ones with a "*" mean they could cause an epileptic seizure!!**)

## Twitch Integration

### What does it do?
It's allowing people in the Twitch chat to vote by typing numbers from 1 to 4 and then from 5 to 8 to affect the effect. The number of the effect wanted is shown on the HUD.

### How to use Twitch Integration?
Easy
1. Complete the [installation guide](#Installation)
3. Open the game
4. Load a save
5. When loaded in, go into the [settings](#Settings) and press "Use OAuth" to log-in.
6. This will open the navigator (Log-in if you are not), then press accept.
7. Go back to sm64coopdx, close the menu and play the game, voilà!

## All the events
```
- Invisible Mario (Makes the player invisible)
- Reverse Control (Reverses all stick movement)
- Low Gravity (Player will be in low gravity)
- Big Mario (Makes the player 2x his size; hitboxes are affected too)
- Tiny Mario (Makes the player 0.5x his size; hitboxes are affected too)
- Random Teleport (Makes the player teleport in a random location) [1 TP]
- Kill streak (The player needs to kill any mob under 10 seconds until the event ends)
- No-hit (The player has one HP and cannot heal back until the timer ends)
- Immortality (Makes the player immune to any damage; things that one-shot you keep killing you)
- Swimming (Makes Mario swim in the air; the oxygen meter is present)
- Ad-break! (Makes an ad about my YouTube channel at the bottom of the screen)
- Bad Apple (Makes the game black and white)
- *Random (Makes the game's textures and music completely random)
- 2x More Chaos (Makes the chaos come two times faster)
- What is happening? (Makes all the active effects invisible)
- -1 star (Makes a collected star go back to its original place)
- +1 star (Makes the player collect one random star from any level)
- High Gravity (Player will be in high gravity)
- Ice Physics (Makes all the floors slippery, like ice)
- Super Speed (Player will be faster)
- Snail (Player will move slower)
- /tp ~ ~100 ~ (Player will be teleported high in the sky)
- Random Gravity (Makes the direction of gravity change temporarily)
- Suicide (Player dies)
- I see you (Makes every hostile mob target you and want you dead)
- *4K (Makes the game's quality horrible)
- Longer events (Makes the events last two times longer)
- Water VS Lava (Makes the lava and water change position)
- Random inputs (Makes every input random)
- Kifflom! (Makes every sound effect "Kifflom")
- Mute (Makes the game's music stop)
- First Person (Makes the player's camera into Mario's head)
- Coin Magnet (Makes the player a coin magnet)
```
\* = Could cause an epileptic seizure

## Information

I don't know how to code, so this mod has been created by ChatGPT (Sorry)

**Windows** (Windows 8, Windows 10 and Windows 11) **only** so far

If you want to add a new event [click here](https://github.com/SamLeGamerYB/Sm64coopdx-Chaos-Mod/issues/new?labels=Event%20Req.)

## TO-DO

- [x] Twitch voting system
- [x] Seizure warning
- [ ] Speedrun.com Category


###### ~The End~
