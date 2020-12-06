```
SECTION ONE - COMMERCIAL DOC & DESIGN INTENTIONS -OR- "IT'S LIKE DIE HARD, BUT WITH...
```

```
[c:dd_the-pitch_page]
```
# the-pitch
**Codename DiverDanni** is a **3D, infinite-runner** game **targeting mobile devices** from **low-end_to_bleeding-edge, state-of-the-art** *hardware* using a mix of *cheap, low-poly animation and art*; and a *clean, oversimplified design*...
> > // leaving as much room as possible for more expensive FX (light, particle, noise in materials/shaders andtextures
...and *equally oversimplified quality settings;* developing in *Unity*.
Set entirely undersea *(infinite-diver then...)*, it will have a female diver character, a theme of isolation in the...*and this can't be overstated*...Pants-Shitting-Vastness (PSV) of the sea.
---
```
[c:dd_the-concept_page]
```
# the-concept
> // return to for guidance; simplify when possible .
* An undersea IR; a balance of zen and adrenaline; cover-shooter swipe controls; isolated, thlarger-than-life "the ocean wants you dead".
---
```
SECTION TWO - SOUNDING BOARD OF ELEMENTS (NOT-YET-IMPLEMENTED IN DESIGN)
```

```
[c:dd_the-"get-it-all-out-so-you-can-sift-the-diamonds-from-the-riverbed".notes_page]
```
> // paged by topic; `# notes`, then `## assets` if applicable.

# notes-on-the-art-direction
* I would like the visuals to be of the darker, moodier variety, similar to the visual-noise-driven light-rendering--and low-poly clever-animation-can-create-character-as-much-as-geometry--techniques used in **Playdead's Inside** (thoroughly outlined [here](https://www.youtube.com/watch?v=RdN06E6Xn9E)).
* I would like to apply different noise (and otherwise shader) effects to seperate objects simultaneously. At this time, using the `Screen space - Camera` and locking the camera and/or light configuration--and therefore the effect--onto the desired Object as part of the Prefab, so it'll generate at spawn time, seems like a solution... but wherether it'll work that way is TBD.

# notes-on-asset-store-leveraging
* I've jumped the gun on picking appropriate tools and purchased more Asset Store assets than is probably wise, but they've been having a big sale (ending in ~ 10 hours, I beleive)... so I decided I could justify going a little overboard.
> // There are worse forms of Pandemic retail therapy (see? justifying it EASY). If not for use in free-diving game, then for educational use and future products. Anywho, I did an inventory of Assets I hope to use for this project (very broad; will narrow down and cut candidates through testing and the prototyping process).

# notes-on-the-*where-i'm-coming-from*-(drive-and-game-~~addiction~~-inspiration)
* I'm excited about this project because it'll give me a venue to play with screen-space controls I haven't-yet seen utilized in the IR genre: I want to use a swipe control-scheme ~~reverently inspired by~~ shamelessly stolen from the brilliantly addicting--but sadly outdated--cover-shooters [Epoch](https://www.youtube.com/watch?v=nt3vcJmilqU) and [Epoch 2](https://www.youtube.com/watch?v=xkD57QHmTTE) from [Uppercut Games](https://www.uppercut-games.com/). I love **these controls, the character's response, and the projectile-timing mechanic to time movement.** The **feel/experience** as a whole is immensely satisfying to me.
* I'm also drawing inspiration from the brilliant and **elegant, oversimplified character mechanics and environment composition** in [Alto's Adventure](http://altosadventure.com/) and [Alto's Odyssey](http://www.altosodyssey.com/) by [Team Alto](http://www.altosadventure.com/team/)... specifically the **one-touch jump/hold-to-backflip mechanic** and the **masterfully-composed layers of 2D sprites** and **increment weather system**. Who knows if I can acheive anything similar, but I'm going to try fleshing out the world's bg visuals with a similar aesthetic.

# notes-on-the-genre-and-method-(infinite-runner-conventions)
# ir-conventions-to-keep
* Forced (-z) motion on level `Modules`
# ir-conventions-sto-lose
* 
---
This will need to be segmented due to the Assets I may be able to leverage into the process. I have **two Engines listed to simplify the process of generating an environment made of modules *(listed below)*, but I don't know if I can simplify the process of building the prefabs and assembling them into modules. This may have to be done the hard way *(trial and error)*.

# notes-on-controls/user-feedback...
## ...leveraging-screen-space-for-theuser/agent-"zones"
> // though the game is entirely forward-moving...using the "depth" (or Z-axis), much of the gameplay mechanics will work around using left/right and up/down (X and Y axes, respetively)
* The **User will swipe in whichever direction they wish to move to in relation to the ***screen space - camera***. This **mechanic will use ***what Epoch 1/2 used with cover,*** **but I'll apply this so that the User can move to different `Lanes` to manage the uncontrollable forward-motion--both navigating the terrain** (ie *sandbars, coral, rock-formations...* eventually *twisting caves and chutes*, and also `Lanes` confined by *virtually-invisible, turbulence-driven **Entities of Water Motion*** like *Tides, Currents,* and possibly even ***larger-than-life elements*** like **Maelstroms** and **Kraken tentacles...** that's not too ambitious for a first commercial game, right? 
> > // I know it's too ambitious. I reckon I will let this idea go when I'm damn-well ready!
> > **spits congealing, brown loogie on dirt porch**
* The point is that screen-space will be implemented, simplifying (in-theory) User's interaction with a 3D game by making the input/feedback as entirely 2D as possible -- the hope is that this approach will make interacting with dangerous elements of the environment--like large/predatory fauna, sharp flora, jagged-structures, to say nothing about [drowning](https://www.gohawaii.com/trip-planning/travel-smart/ocean-safety-in-hawaii) in the Pacific Ocean--much more instinctual and make any learning curve as flat as possible while keeping the adrenaline/zen balance intact.

# notes-on-the-maths...
> // here's where your scratch math work can go

# ...notes-on-the-unsorted-(blahblahblah-shit-i-gotta-get-out-to-get-to-the-productive-stuff)
> > /* list of **keywords** to keep sights on big-picture while developing [updated 12-05-2020]: pants-shitting-vastness, PSV,
* The above inspirations drive my interest in this project--I'd have no interest in making a simplified action game, an infinite-runner, an enigmatic, mood-driven game world, or even a mobile game in particular if I hadn't foud the Epoch games, the Alto's games, or Playdead's INSIDE (because of which, I also played and loved Limbo). With that said, there are loads of other concerns creating a prototype (let alone a commercial game) comes with. For these, I have my sensibilities of being an iPhone/Chromebook/Windows-Laptop user (power-user in most cases), but of the design and usability decisions I'll make, right now the clearest guide I've chosen is a the book [Don't Make Me Think: A Common Sense Approach to Web ^and Mobile Usability (Voices That Matter) Revisited by Steve Krug](https://www.amazon.com/Dont-Make-Think-Revisited-Usability/dp/0321965515/ref=pd_lpo_14_t_0/138-6845820-2462336?_encoding=UTF8&pd_rd_i=0321965515&pd_rd_r=4b2e4083-5f9d-48f8-ba19-039328bf73b2&pd_rd_w=WDLJz&pd_rd_wg=KoA1k&pf_rd_p=7b36d496-f366-4631-94d3-61b87b52511b&pf_rd_r=NMTGRDJ1ZCDTNQAQM7G3&psc=1&refRID=NMTGRDJ1ZCDTNQAQM7G3).
> > // ooh! also, I gotta be careful implementing the, uh, probably irresponsible amount of Unity Asset Store assets I "purchased" (several were at no cost)

---
```
SECTION THREE - NEEDS TO MEET & ASSETS TO MEET THEM
// page-sorted by category
```
```
[c:dd_the-2d_page]
```
# needs
*
# assets
* DAVID STENFORS' `Animated Loading Icons`
* FUNKYCODE's `Smart Lighting 2D`
* UNITY TECHNOLOGIES' `Unity Anima2D`
# choices
* 
---
```
[c:dd_the-art_page]
```
# needs...
## ...concept-art...
### ...by-hand
> // graph paper; mostly needs too small or specific to be met by third-party assets.
* 
# assets
* RPGWHITELOCK's `ALLSky - 200+ Sky / Skybox Set`

# decisions
*

---
```
[c:dd_the-agents_page]
```
# needs
* SONGGAMEDEV's `Tower Defense Toolkit 4 (TDTK-4)`
# assets
* 
# decisions
*
---
```
[c:dd_the-camera_page]
```
# needs
* 
# assets
* ROAD TURTLE GAMES' `MilkShake Camera Shaker`
# decisions
* 
```
[c:dd._the-controls_page]
```
# needs
* Swipe-controls  // shooting for similar feel to uppercut's Epoch/Epoch 2 - The User will swipe in whichever direction they need to move to. This mechanic will use what Epoch 1/2 used with cover, but I'll apply this so that the User can move to different `Lanes` to move forward through, both navigating the terrain *(sandbars, coral, rock-formations...eventually twisting caves and chutes, and also confined lanes made from currents and confined by turbulence from `Entities of Water Motion` like Tides, Currents, possibly larger-than-life elements like Maelstroms and Kraken tentacles...that's not too ambitious for a first commercial game, right? (Note: I know it's too ambitious, I'll let this idea go when I'm ready.)*, and interacting with dangerous elements of the environment *(large and predatory fauna, sharp flora, jagged manmade/natural structures)*
# assets
* 
# choices
*
---
---
```
[c:dd_the-learning-daemons_page
```
# needs
* 
# assets
* ALEXANDER PETRAEV's `Deep Components Free`
# decisions
*
---
```
[c:dd_the-fx_page]
```
# needs

# assets...
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
# decisions
*
---
```
[c:dd_the-interfaces-(interfi?)_page]
```
# needs
* 
# assets
* BEFFIO's `UI - Builder`
* IULIANA U's `Mobile Game Outline UI Kit`
* PUSZKAREK's `Minilamist Icons`
* OFFICE57's `64 Flat Game Icons`
* SLIMEUI's `3D Modern Menu`
* SOTI's `Modern & Clean GUI`
# decisions
* 
---
```
[cdd:the-levels_page]
```
# needs...
## ...modules 
# assets
* 
# decisions
*
```
[c:dd_the-materiails_page]
```
# needs
* 
# assets
* CASUAL2D's `Snow Cliff Materials`
* CIATHYZA's `Gridbox Prototype Materials`
* JEAN MORENO (JMO)'s `Free MatCap Shaders`
* NOBIAX/YUGHUES's `Yughes Free Ground Materials`
# decisions
* 
---
```
-[c:dd_the-maths_page]
```
# needs...
## ...forward-motion
* The Gravity of--or Force exerted on--the Level `Modules` moving around the User will start with...
> // Assuming a screen of 16x9 Units (common ratio on mobile devices).
  a. baseline speed = ~8-10 u/s	// this is the ~gravity force setting in Unity, yeah?
  b. hindered speed = ~7-8 u/s
  c. boosted speed = ~10-13 u/s
> > // units will probably = meters, but I'll commit to the metric system when I'm emotionally mature enough to let go of my Kraken idea.
# assets
* 
# decisions
* 
```
[c:dd_the-meshes_page]
```
# needs
* 
# assets...
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
# decisions
* 
---
```
[c:dd_the-navigation_page]
```
# needs
* 
# assets
* ARON GRANBERG's `A* Pathfinding Project`
* VISUALWORKS' `NavMesh Cleaner`
# decisions
* 
---
```
[c:dd_the-physics_page]
```
# needs
* 
# assets
* EDY's `Edy's Vehicle Physics`
# decision
* 
---
```
[c:dd_the-procedural-content-generation_page]
```
# needs
* 
# assets
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
# decisions
---
```
[c:dd_the-sounds_page]
```
# needs
* 
# assets...
## ...diagetic
* CAFOFO's `Water Sounds Pack`
## ...muzak
* DARK TONIC INC.'s `Master Audio: AAA Sound`
* JOHN LEONARD FRENCH's `The Combat Collection PRO edition`
## ...other/non-diegetic
* 
# decisions
* 
---
```
[c:dd_the-scripts_page]
```
# needs
* 
# assets...
## ...code
* DOTBUNNY's `VSCode`
## ...troubleshooting
* FLIPBOOK GAMES' `Script Inspector 3`
## ...visual
* UNITY TECHNOLOGIES'
  - `Bolt`
  - `Bolt Kit: Third Person for Unity`
# decisions
* 
---
```
SECTION FOUR - THE PROTOTYPE DEVELOPMENT
```
```
[c:dd_the-prototype_page]
// heavily oversimplified into what works and what doesn't; brief explanations when deemed absolutely necessary.
```
# prototype-needs
* 
# prototype-assets
* 
# prototype-decisions
*

---
```
SECTION FIVE - THE PREPRODUCTION PLAN
// based on choices made in prototype development.
```
```
[c:dd_the-preproduction-plan_page]
```
# needs
* 
# assets
* 
# decisions
* 
---
```
SECTION SIX - PRODUCTION PIPELINE [DEVLOG -OR- TRANSCRIPT OF COMPLETED TASKS]
```
```
[c:dd_the ]
```
# needs
* 
# assets
* 
# decisions
*

---
```
SECTION SEVEN - THE LEFTOVERS`
```
```
[c:dd_the-leftovers_page]
// the-delicious-leftovers-you'll-heat-up-and-eat-for-lunch-(the-next-project)-tomorrow.
```
# needs
* 
# assets:
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
# decisions
* 
