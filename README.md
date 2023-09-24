# endleZZ
A (silly) tiny javascript infinite zombie game
![endleZZ-v02b](https://github.com/TheRoam/endleZZ/assets/63456390/40a1b368-92af-43c6-9956-e04134ac0067)

## Description
You are a survivor with unlimited ammo surrounded by zombies, how long can you survive?

**Randomness** will make every game **unique**: zombie enemies are randomly generated in random border locations with random attributes (speed and level).

There are 4 zombie levels, making them bigger and harder to kill (1x1, 2x2, 3x3, 4x4).

The game is **infinite** as long as you can keep up killing zombies.

Wasting ammo reduces your score though, so make accurate shots!

## Game instructions
1. Click or touch a point in the map to shoot to that place.
2. Every bullet used deduces 1 point (-1).
3. Shooting body parts (light green) adds 1 point (+1).
4. Shooting in the head (dark green) adds 10 points (+10).
5. Survival time will also add score points in the future.

## Game installation
**endleZZ** is an infinite zombie survival game developed in javascript, making it available for any device with an internet browser.

Despite of this, the game can be played offline, running the .html file locally anywhere.

Otherwise, you can play the **online release** version which I host in my server.

## Online release
[https://theroamingworkshop.cloud/endlezz](https://theroamingworkshoo.cloud/endlezz)

## Current features
* Multi-platform
* Portable (single .html executable)
* Lightweight: 20 KB
* Offline: download and play locally.
* Infinite survival game
* Random map generation
1. Trees
2. Rocks
* Random weather conditions
1. Cloud generation
* Random enemy spawn time
* Random enemy spawn location
* Random enemy features
1. Speed
2. Level
* Modular enemies (multi-part)
1. Body (light green)
2. Head (dark green)
* Complex scoring system
1. (Hit) Body hit +1
2. (Kill) Head shot +10
3. (Bullet) Used bullet -1
4. (Time) Survival time [Not implemented]

## Feature brainstorming:
* options menu: instructions
* final score summary page
* more complex graphics
* day-night cycle
* weather system: add rain
* map objects: walls
* complex enemies
* enemy looting
* player special attacks/combos/weapos

## Changelog

Project launch: 23-09-2022

### v 0.1 Proof of concept
Release: 25-09-2022
- created player object centered on screen
- created bottom menu for game info and controls
- created intro loading screen that triggers full screen
- created zombie objects that randomly spawn on borders
- created zombie levels as bigger objects harder to defeat
- created bullet object
- bullet object moves to cursor click
- created collision detector
- collision removes zombie level objects
- collision adds hit and kill stats
- collision of zombie with player ends the game
- collisions update text (hit, kill, you died)
- bottom stats show zombies spawned
- bottom stats show game time
- bottom stats show score
- zombie object moves to player object using animation
- zombie object animation when reaching player
- player object death animation
- created restart game option after death
- created initial warning message for copyright
### v 0.1.1 Initial bugfix
Release: 28-09-2022
- disabled user-select so game text is now not selectable
- adjusted warning size
- created function to check origin and display warning accordingly
### v 0.2.0 Anniversary update
Release: 23-09-2023
- added options menu
- added timing controls: pause, restore, quit
- graphics improvements: game objects
- weather system: random cloud generation
- added instructions page
- bullets now reach the end of the screen despite where you click
- overall performance and interaction improvements
### v 0.2.1 Minor styling
Release: 24-09-2023
- fixed menu background display
- added zombie eyes
