# codename-DiverDanni

## the-pitch
**Codename DiverDanni** is a 3D Infinite-Runner game targeting Mobile devices.
It is set entirely undersea *(infinite-diver then...)* and have a female diver character. The game's mood/feel of isolation within--*and this can't be overstated*-the Pants-Shitting-Vastness (PSV) of the sea. Codename Diver Danni will be developed in Unity.

## concepual-notes
* I'm excited about this project because it'll give me a venue to play with screen-space controls I haven't-yet seen utilized in the IR genre: I want to use a swipe control-scheme inspired by (shamelessly stolen from) the brilliantly addicting (but sadly outdated) cover-shooters [Epoch](https://www.youtube.com/watch?v=nt3vcJmilqU) and [Epoch 2](https://www.youtube.com/watch?v=xkD57QHmTTE) from [Uppercut Games](https://www.uppercut-games.com/). I love these controls. They have been immensely satisfying to me.

* I'm also drawing inspiration from the brilliant and beautifully-oversimplified character mechanics and environment creation in [Alto's Adventure](http://altosadventure.com/) and [Alto's Odyssey](http://www.altosodyssey.com/) by [Team Alto](http://www.altosadventure.com/team/)... specifically the one-touch jump/hold-to-backflip mechanic and the masterfully-composed layers of 2D sprites and increment weather. Who knows if I can acheive anything similar, but I'm going to try fleshing out the world's bg visuals with a similar aesthetic.
  Developing in Unity.

## leveraging-screen-space
* I would like the visuals to be of the darker, moodier variety, similar to the visual-noise-driven light-rendering--and low-poly clever-animation-can-create-character-as-much-as-geometry--techniques used in **Playdead's Inside** (thoroughly outlined [here](https://www.youtube.com/watch?v=RdN06E6Xn9E).
* I would like to apply different noise (and otherwise shader) effects to seperate objects simultaneously. At this time, using the `Screen space - Camera` and locking the camera and/or light configuration--and therefore the effect--onto the desired Object as part of the Prefab, so it'll generate at spawn time, seems like a solution... but wherether it'll work that way is TBD.

### User/Agent Screen-space Zones
> // though the game is entirely forward-moving...using the "depth" (or Z-axis), much of the gameplay mechanics will work around using left/right and up/down (X and Y axes, respetively)
* The User will swipe in whichever direction they need to move to. This mechanic will use what Epoch 1/2 used with cover, but I'll apply this so that the User can move to different `Lanes` to move forward through, both navigating the terrain *(sandbars, coral, rock-formations...eventually twisting caves and chutes, and also confined lanes made from currents and confined by turbulence from `Entities of Water Motion` like Tides, Currents, possibly larger-than-life elements like Maelstroms and Kraken tentacles...that's not too ambitious for a first commercial game, right? (Note: I know it's too ambitious, I'll let this idea go when I'm ready.)*, and interacting with dangerous elements of the environment *(large and predatory fauna, sharp flora, jagged structures)*
> > 
### swipe controls

## Infinite-Runner-conventions
### IRC's-to-keep
> // Infinite Runner Conventions I want included
* Forced motion on level `Modules`
> > // wouldn't be an IR if you got to stop and take breathers.

### IRC's-to-lose // Infinite Runner Conventions to exclude

## the-math-so-far:
### forward-motion
*Assuming a screen of **16x9 Units** (common ratio on mobile devices; units will probably = meters, but I'll commit to the metric system when I'm emotionally mature enough to let go of my Kraken idea.)*
* The Gravity of--or Force exerted on--`User` (actually the `Level Modules` moving around the User) will start with...
  a. baseline speed = ~8-10 u/s
  b. hindered speed = ~7-8 u/s
  c. boosted speed = ~10-13 u/s

## approach-to-modules-and-PGC
This will need to be segmented due to the Assets I may be able to leverage into the process. I have **two Engines listed to simplify the process of generating an environment made of modules *(listed below)*, but I don't know if I can simplify the process of building the prefabs and assembling them into modules. This may have to be done the hard way *(trial and error)*.

# Leveraging-the-Asset-Store
* I've jumped the gun on picking appropriate tools and purchased more Asset Store assets than is probably wise, but they've been having a big sale (ending in ~ 10 hours, I beleive)... so I decided I could justify going a little overboard.
> // There are worse forms of Pandemic retail therapy (see? justifying it EASY). If not for use in free-diving game, then for educational use and future products. Anywho, here's a list of Assets I hope to use for this project (very broad; will narrow down and cut candidates through testing process).
## purchased-assets
> // *alphabetical by author; some are not licensed for commercial use...acknowledged*
* ALEXANDER PETRAEV's `Deep Components Free`
* AMPLIFY CREATIONS' `Amplify Occlusion`
* ARON GRANBERG's `A* Pathfinding Project`
* BEFFIO's `UI - Builder`
* BITGEM's `Micro Monster & Heroes Pack Low Poly`
* BLACK HORIZON STUDIOS' `Unistorm - Volumetric Clouds, Sky, Modular Weather, and Cloud Shadows`
* CAFOFO's `Water Sounds Pack`
* CASUAL2D's `Snow Cliff Materials`
* CATALIN PAVEL's `Low Poly Free Vegetation Pack`
* CIATHYZA's `Gridbox Prototype Materials`
* DARK TONIC INC.'s `Master Audio: AAA Sound`
* DAVID STENFORS' `Animated Loading Icons`
* DAVIT NASKIDASHVILI's `Curved World (2020)`
* DAVIT NASKIDASHVILI's `Dynamic Radial Masks`
* DAVIT NASKIDASHVILI's `Low Poly Mesh Generator` - ***TESTED: very easy and useful for a newbie dipshit like me; IFL it because my art direction includes an MPV for collections of triangle that vaguely resemble the (PSV of the) ocean.***
* EDY's `Edy's Vehicle Physics`
* ECHO17's `SimpleSQL`
* THE DEVELOPER's `Cool Visual Effects - Part 1 - URP Support`
* DOTBUNNY's `VSCode`
* FLIPBOOK GAMES' `Script Inspector 3`
* FORST's `Oak Trees Package`
* FUNKYCODE's `Smart Lighting 2D`
* IULIANA U `Mobile Game Outline UI Kit`
* JANPEC's `Underwater life deluxe`
* JUAN RODRIGUEZ's `Procedural Level Generator`
* JEAN MORENO (JMO)'s `Free MatCap Shaders`
* JOHN LEONARD FRENCH's `The Combat Collection PRO edition`
* JOLIX's `Low Poly Water GPU`
* JOSH H's `Procedural UI Image`
* JUSTCREATE's `Low-Poly Simple Nature Pack`
* LB3D's `Fibonacci Arrays [Optimal Spacing Script]`
* Long BUNNY LABS' `Boing Kit: Dynamic Bouncy Bones, Grass, Water, and More`
* LONG BUNNY LABS' `MudBun: Volumetric VFX Mesh Tool`
* MANUFACTURA K4's `Top-Down Assets`
* MARCUS VINICIUS DA SILVA's `TrackGen - A Procedural Track Generator`
* MASATATSU NAKAMURA's `Teddy`
* MOBFARM's `AutoPool`
* MOREMOUNTAINS' `MMFeedbacks`

## purchased-assets

### 2D-suited-tools
* UNITY TECHNOLOGIES' `Unity Anima2D`

### art-suited-tools
* RPGWHITELOCK's `ALLSky - 200+ Sky / Skybox Set`

### agent-creation-and-management-suited-tools
* SONGGAMEDEV's `Tower Defense Toolkit 4 (TDTK-4)`

### camera-suited-tools
* ROAD TURTLE GAMES' `MilkShake Camera Shaker`

### controller-suited-tools
* SCSM's `Sci-Fi Ship Controller`

### editor-suited-tools
* MHLAB's `AutoSaver - Don't waste time anymore!`

### fx-suited-tools
#### lighting-fx
* **RAPHAEL ERNAELSTEN's** `Aura 2 - Volumetric Lighting & Fog`
> > // favorite
#### particle-fx
* SYNTY STUDIOS' `POLYGON - Particle FX`
* UNITY TECHNOLOGIES'
  - `Unity Particle Pack`
  - `Unity Particle Pack 5.x`

### prefab-suited-tools

### procedural-content-generation-suited-tools
* ANDASOFT's `EasyRoads3D Pro V3`
* DREAMTECK's `Forever - Endless Runner Engine`
* MOREMOUNTAINS' `2D+3D Infinite Runner Engine`
* PATH-O-LOGICAL GAMES' `PoolManager`

### navigation-suited-tools
* VISUALWORKS' `NavMesh Cleaner`

### materials-and-shaders-suited-tools
* NOBIAX/YUGHUES's `Yughes Free Ground Materials`
* PLACEHOLDER SOFTWARE's `Wet Stuff`

### mesh-suited-tools
#### mesh-creation-and-management
* ROCKBUILDER's `RockBuilder`
#### mesh-premade-packs
* **POLYPERFECT's**
  - `Low Poly Animated Animals`
  - `Low Poly Animated People`
* SYNTY STUDIOS' `POLYGON - Starter Pack`
* UNITY TECHNOLOGIES' `3D Game Kit - Props Pack`
* VINTAGESOFT's `Sea Animals Pack LowPoly V1`

### music-suited-tools

### scripting-suited-tools
* UNITY TECHNOLOGIES'
  - `Bolt`
  - `Bolt Kit: Third Person for Unity`

### ui/ux-suited-tools
* OFFICE57's `64 Flat Game Icons`
* PUSZKAREK's `Minimalist Icons`
* SLIMUI's `3D Modern Menu`
* SOTI's `Modern & Clean GUI`
* SUB-C's `Shaped 2D - Procedural sprites and UI`

### water-suited-tools
* PINWHEEL STUDIO's `Low Poly Water - Builtin & URP - Poseidon`
* TANUKI DIGITAL's `SUIMONO Water System`

## ***tools-probably-more-suited-for-other-projects***
* POLYGON MAKER's `Fantasy Horde - Orc`
* PROTOFACTOR, INC's `GOLEM`
* RICIMI's `Frozen GUI Pack`
* SICS GAMES' `Toon Racing`
* UNITY EDUCATION's `Endless Runner Assets`
* UNITY TECHNOLOGIES'
  - `2D Game Kit`
  - `Book Of The Dead: Environment`
  - `Lost Crypt - 2D Sample Project`
  - `Moody Tunes - LEGO Microgame Add-Ons`
  - `Moody Skies - LEGO Microgame Add-Ons`
  - `Standard Assets (for Unity 2018.4)`
