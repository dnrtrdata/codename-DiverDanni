`SECTION ONE - COMMERCIAL DOC & DESIGN INTENTIONS -OR- "IT'S LIKE DIE HARD, BUT WITH...`
`===`

[c:dd_A]
# the-concept
> // return to for guidance; simplify when possible .
* An undersea IR; a balance of zen and adrenaline; cover-shooter swipe controls; isolated, thlarger-than-life "the ocean wants you dead".

# the-pitch
**Codename DiverDanni** is a **3D, infinite-runner** game **targeting mobile devices** from **low-end_to_bleeding-edge, state-of-the-art** *hardware* using a mix of *cheap, low-poly animation and art*; and a *clean, oversimplified design*...
> > // leaving as much room as possible for more expensive FX (light, particle, noise in materials/shaders andtextures
...and *equally oversimplified quality settings;* developing in *Unity*.
Set entirely undersea *(infinite-diver then...)*, it will have a female diver character, a theme of isolation in the...*and this can't be overstated*...Pants-Shitting-Vastness (PSV) of the sea.

---
`SECTION TWO - SOUNDING BOARD OF ELEMENTS (NOT-YET-IMPLEMENTED IN DESIGN)`
`===`

[c:dd_B]
# notes-on...
> // paged by topic; `# notes`, then `## assets` if applicable.

## ...notes-on-the-art-direction
* I would like the visuals to be of the darker, moodier variety, similar to the visual-noise-driven light-rendering--and low-poly clever-animation-can-create-character-as-much-as-geometry--techniques used in **Playdead's Inside** (thoroughly outlined [here](https://www.youtube.com/watch?v=RdN06E6Xn9E).
* I would like to apply different noise (and otherwise shader) effects to seperate objects simultaneously. At this time, using the `Screen space - Camera` and locking the camera and/or light configuration--and therefore the effect--onto the desired Object as part of the Prefab, so it'll generate at spawn time, seems like a solution... but wherether it'll work that way is TBD.

## ...notes-on-the-*where-i'm-coming-from*-(drive-and-game-~~addiction~~-inspiration)
* I'm excited about this project because it'll give me a venue to play with screen-space controls I haven't-yet seen utilized in the IR genre: I want to use a swipe control-scheme ~~reverently inspired by~~ shamelessly stolen from the brilliantly addicting--but sadly outdated--cover-shooters [Epoch](https://www.youtube.com/watch?v=nt3vcJmilqU) and [Epoch 2](https://www.youtube.com/watch?v=xkD57QHmTTE) from [Uppercut Games](https://www.uppercut-games.com/). I love **these controls, the character's response, and the projectile-timing mechanic to time movement.** The **feel/experience** as a whole is immensely satisfying to me.
* I'm also drawing inspiration from the brilliant and **elegant, oversimplified character mechanics and environment composition** in [Alto's Adventure](http://altosadventure.com/) and [Alto's Odyssey](http://www.altosodyssey.com/) by [Team Alto](http://www.altosadventure.com/team/)... specifically the **one-touch jump/hold-to-backflip mechanic** and the **masterfully-composed layers of 2D sprites** and **increment weather system**. Who knows if I can acheive anything similar, but I'm going to try fleshing out the world's bg visuals with a similar aesthetic.

## ...notes-on-the-genre-and-method-(approach-to-infinite-runners/modules/procedural-content-generation)
This will need to be segmented due to the Assets I may be able to leverage into the process. I have **two Engines listed to simplify the process of generating an environment made of modules *(listed below)*, but I don't know if I can simplify the process of building the prefabs and assembling them into modules. This may have to be done the hard way *(trial and error)*.

## ...notes-on-controls/user-feedback...
### ...leveraging-screen-space.user/agent-ss-zones
> // though the game is entirely forward-moving...using the "depth" (or Z-axis), much of the gameplay mechanics will work around using left/right and up/down (X and Y axes, respetively)
* The **User will swipe in whichever direction they wish to move to in relation to the ***screen space - camera***. This **mechanic will use ***what Epoch 1/2 used with cover,*** **but I'll apply this so that the User can move to different `Lanes` to manage the uncontrollable forward-motion--both navigating the terrain** (ie *sandbars, coral, rock-formations...* eventually *twisting caves and chutes*, and also `Lanes` confined by *virtually-invisible, turbulence-driven **Entities of Water Motion*** like *Tides, Currents,* and possibly even ***larger-than-life elements*** like **Maelstroms** and **Kraken tentacles...** that's not too ambitious for a first commercial game, right? 
> > // I know it's too ambitious. I reckon I will let this idea go when I'm damn-well ready!
> > **spits congealing, brown loogie on dirt porch**
* The point is that screen-space will be implemented, simplifying (in-theory) User's interaction with a 3D game by making the input/feedback as entirely 2D as possible -- the hope is that this approach will make interacting with dangerous elements of the environment--like large/predatory fauna, sharp flora, jagged-structures, to say nothing about [drowning](https://www.gohawaii.com/trip-planning/travel-smart/ocean-safety-in-hawaii) in the Pacific Ocean--much more instinctual and make any learning curve as flat as possible while keeping the adrenaline/zen balance intact.

## ...notes-on-the-maths...
### ...forward-motion
* The Gravity of--or Force exerted on--the Level `Modules` moving around the User) will start with...
  a. baseline speed = ~8-10 u/s
  b. hindered speed = ~7-8 u/s
  c. boosted speed = ~10-13 u/s
> // Assuming a screen of 16x9 Units (common ratio on mobile devices).
> > // units will probably = meters, but I'll commit to the metric system when I'm emotionally mature enough to let go of my Kraken idea.

## ...notes-on-the-unsorted
> > /* list of **keywords** to keep sights on big-picture while developing [updated 12-05-2020]: pants-shitting-vastness, PSV,
* The above inspirations drive my interest in this project--I'd have no interest in making a simplified action game, an infinite-runner, an enigmatic, mood-driven game world, or even a mobile game in particular if I hadn't foud the Epoch games, the Alto's games, or Playdead's INSIDE (because of which, I also played and loved Limbo). With that said, there are loads of other concerns creating a prototype (let alone a commercial game) comes with. For these, I have my sensibilities of being an iPhone/Chromebook/Windows-Laptop user (power-user in most cases), but of the design and usability decisions I'll make, right now the clearest guide I've chosen is a the book [Don't Make Me Think: A Common Sense Approach to Web ^and Mobile Usability (Voices That Matter) Revisited by Steve Krug](https://www.amazon.com/Dont-Make-Think-Revisited-Usability/dp/0321965515/ref=pd_lpo_14_t_0/138-6845820-2462336?_encoding=UTF8&pd_rd_i=0321965515&pd_rd_r=4b2e4083-5f9d-48f8-ba19-039328bf73b2&pd_rd_w=WDLJz&pd_rd_wg=KoA1k&pf_rd_p=7b36d496-f366-4631-94d3-61b87b52511b&pf_rd_r=NMTGRDJ1ZCDTNQAQM7G3&psc=1&refRID=NMTGRDJ1ZCDTNQAQM7G3).
> > // ooh! also, I gotta be careful implementing the, uh, probably irresponsible amount of Unity Asset Store assets I "purchased" (several were at no cost)

---
`SECTION THREE - SUPPORTED, LIFTED, AND SEPARATED ELEMENTS (SORTED BY TOPIC-OF-CONCERN [PULL FROM THESE PAGES FOR PREPRODUCTION PIPELINE])`
`===`

[c:dd.01]
# the-controls...
## ...swipe-controls  // shooting for similar feel to uppercut's epoch/epoch 2
* The User will swipe in whichever direction they need to move to. This mechanic will use what Epoch 1/2 used with cover, but I'll apply this so that the User can move to different `Lanes` to move forward through, both navigating the terrain *(sandbars, coral, rock-formations...eventually twisting caves and chutes, and also confined lanes made from currents and confined by turbulence from `Entities of Water Motion` like Tides, Currents, possibly larger-than-life elements like Maelstroms and Kraken tentacles...that's not too ambitious for a first commercial game, right? (Note: I know it's too ambitious, I'll let this idea go when I'm ready.)*, and interacting with dangerous elements of the environment *(large and predatory fauna, sharp flora, jagged manmade/natural structures)*

---

[c:dd.02]
# infinite-runner-conventions...
## ...irc's-to-keep
* Forced motion on level `Modules`
## ...to-lose
* 

---

[c:dd.03]
# leveraging-the-asset-Store...
* I've jumped the gun on picking appropriate tools and purchased more Asset Store assets than is probably wise, but they've been having a big sale (ending in ~ 10 hours, I beleive)... so I decided I could justify going a little overboard.
> // There are worse forms of Pandemic retail therapy (see? justifying it EASY). If not for use in free-diving game, then for educational use and future products. Anywho, here's a list of Assets I hope to use for this project (very broad; will narrow down and cut candidates through testing process).

## ...the-assets-available-for-development...

### ...the-2nd-dimension
* FUNKYCODE's `Smart Lighting 2D`
* UNITY TECHNOLOGIES' `Unity Anima2D`

---
# the-art
* RPGWHITELOCK's `ALLSky - 200+ Sky / Skybox Set`

---
# agent-creation-and-management-suited-tools
* 
* SONGGAMEDEV's `Tower Defense Toolkit 4 (TDTK-4)`

---
# the-camera
* 
* ROAD TURTLE GAMES' `MilkShake Camera Shaker`

---
# the-learning-daemons
* * ALEXANDER PETRAEV's `Deep Components Free`

---
# the-fx...
## ...lighting-fx
* AMPLIFY CREATIONS' `Amplify Occlusion`
* RAPHAEL ERNAELSTEN's `Aura 2 - Volumetric Lighting & Fog` // fav
## ...particle-fx
* THE DEVELOPER's `Cool Visual Effects - Part 1 - URP Support`
* SYNTY STUDIOS' `POLYGON - Particle FX`
* UNITY TECHNOLOGIES'
  - `Unity Particle Pack`
  - `Unity Particle Pack 5.x`
## ...material-and-shader-fx
* DAVIT NASKIDASHVILI's `Dynamic Radial Masks`
* LONG BUNNY LABS' `MudBun: Volumetric VFX Mesh Tool`
> > // fav
* DAVIT NASKIDASHVILI's `Curved World (2020)`
* PLACEHOLDER SOFTWARE's `Wet Stuff`
## ...water-fx
* JANPEC's `Underwater life deluxe`
* JOLIX's `Low Poly Water GPU`
> > // fav
* PINWHEEL STUDIO's `Low Poly Water - Builtin & URP - Poseidon`
* RIVERMILL STUDIO's - `Underwater FX`
* TANUKI DIGITAL's `SUIMONO Water System`
## ...weather-fx
* BLACK HORIZON STUDIOS' `Unistorm - Volumetric Clouds, Sky, Modular Weather, and Cloud Shadows`

---
# the-interfaces-(the-interfi[?]) 
* BEFFIO's `UI - Builder`
* DAVID STENFORS' `Animated Loading Icons`
* IULIANA U's `Mobile Game Outline UI Kit`
* PUSZKAREK's `Minilamist Icons`
* OFFICE57's `64 Flat Game Icons`
* SLIMEUI's `3D Modern Menu`
* SOTI's `Modern & Clean GUI`

---
# the-materiails
* CASUAL2D's `Snow Cliff Materials`
* CIATHYZA's `Gridbox Prototype Materials`
* JEAN MORENO (JMO)'s `Free MatCap Shaders`
* NOBIAX/YUGHUES's `Yughes Free Ground Materials`

---
# the-meshes...
## ...creation
* MASATATSU NAKAMURA's `Teddy`
## ...management
* DAVIT NASKIDASHVILI's `Low Poly Mesh Generator`
> > // tested: very easy and useful for a newbie dipshit like me; IFL it because my art direction includes an MPV for collections of triangle that vaguely resemble the ocean (jaw-dropping-beauty; bright, big-eyed adorability; and PSV all considered).
## ...third-party-packs
* CATALIN PAVEL's `Low Poly Free Vegetation Pack`
* DMITRIY DRYZHAK's
	- `Corals`
	- `Corals 2`
* JUSTCREATE's `Low-Poly Simple Nature Pack`
* *POLYPERFECT's*
  - `Low Poly Animated Animals` // fav; use as baseline for low-poly/vertex count to match higher-complexity assets throughout
  - `Low Poly Animated People`
* SYNTY STUDIOS' `POLYGON - Starter Pack`
* UNITY TECHNOLOGIES' `3D Game Kit - Props Pack`
* VINTAGESOFT's `Sea Animals Pack LowPoly V1` // fav

---
### the-navigation
* ARON GRANBERG's `A* Pathfinding Project`
* VISUALWORKS' `NavMesh Cleaner`

---
# the-physics
* * EDY's `Edy's Vehicle Physics`

---
# the-procedural-content-generation
* ANDASOFT's `EasyRoads3D Pro V3`
* DREAMTECK's `Forever - Endless Runner Engine`
* JOSH H's `Procedural UI Image`
* JUAN RODRIGUEZ's `Procedural Level Generator`
* LB3D's `Fibonacci Arrays [Optimal Spacing Script]`
* MARCUS VINICIUS DA SILVA's `TrackGen - A Procedural Track Generator`
* MOREMOUNTAINS' `2D+3D Infinite Runner Engine`
* MOBFARM's `AutoPool`
* PATH-O-LOGICAL GAMES' `PoolManager`
* ROCKBUILDER's `RockBuilder`
* 

---
# the-sound...

## ...diagetic
* CAFOFO's `Water Sounds Pack`
## ...muzak
* DARK TONIC INC.'s `Master Audio: AAA Sound`
* JOHN LEONARD FRENCH's `The Combat Collection PRO edition`
## ...other/non-diegetic
* 

---
# the-scripts...
## ...code
* DOTBUNNY's `VSCode`

## ...troubleshooting
* FLIPBOOK GAMES' `Script Inspector 3`

## ...visual
* UNITY TECHNOLOGIES'
  - `Bolt`
  - `Bolt Kit: Third Person for Unity`

---
`SECTION FOUR - THE PROTOTYPE`
===
[c:dd.04]
# 


---
`SECTION FOUR - PREPRODUCTION [PIPELINE] PLAN`
===
[c:dd.05]
# 

---
`SECTION SIX - PRODUCTION PIPELINE [DEVLOG -OR- TRANSCRIPT OF COMPLETED TASKS]`
===
[c:dd.06]
#

---
`SECTION SEVEN - THE LEFTOVERS`
===
[c:dd.(N/A)]
# ***the-delicious-leftovers-you'll-heat-up-and-eat-for-lunch-(the-next-project)-tomorrow***
* BITGEM's `Micro Monster & Heroes Pack Low Poly`
* ECHO17's `SimpleSQL`
* FORST's `Oak Trees Package`
* MANUFACTURA K4's `Top-Down Assets`
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
