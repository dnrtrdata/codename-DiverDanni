# DESIGNING THE SANDBOX LIMITATIONS
## A. PROTOTYPE
### LOADING/ONBOARDING
* HEY DEVICE, LISTEN FOR WHEN THE PLAYER PRESSES MY GAME'S ICON, ALERT MY GAME TO DO IT'S THING WHEN ; SHOW A SPLASH/LOADING SCREEN, BEGIN LOADING UI ASSETS, AND DISPLAY THE UI WHEN IT IS LOADED.

* the Device will listen for the player and instruct the Game to load when the player presses the game's icon;
// need `a game icon` -- here's something for now: ![](.png)

* the Game will load the user interface, but will display a splash/loading screen that will fade out when the user interface is done loading;
// need a `remedial user interface` that has `one design element conveying the the game's diving concept` and `three buttons: a "play" button, a "settings" button, and a joke button we'll call the "a third option" button` (maybe a link to an article about the ocean wanting you dead... [that didn't take long to find](https://www.cracked.com/article_21612_5-insane-things-deadliest-catch-leaves-out-about-my-job.html))


## B. GAME
### LOADING/ONBOARDING
*

---
# NTS ON BELOW ITEMS
  - BELOW IS THE WORD-VOMIT REMNANTS OF THE GAME'S ORIGINAL INTENTION
  - NOW THE FOCUS IS ON WHAT I WOULD LIKE THE GAME TO DO `(IN THE FORM OF SOMETHING LIKE: "HEY SOFTWARE, PLEASE LISTEN FOR THE PLAYER DOING THIS, THIS, OR THIS; IF THEY DO THE FIRST THING, DO THIS AND LISTEN FOR THIS; IF THEY DO THIS OTHER THING, DO THIS INSTEAD; IF THEY DO NONE OF THESE THINGS, PLEASE DO THIS THING NEXT." )`
  - DON'T REMOVE THE BELOW THINGS, BUT ONLY USE THEM FOR REFERENCE AS THE GAME'S INTENTION

```
SECTION ONE - COMMERCIAL DOC & DESIGN INTENTIONS -OR- "IT'S LIKE DIE HARD, BUT WITH...
```

```
[c:dd_the-pitch_plan]
```
# the-pitch
**Codename DiverDanni** is a 3D, infinite-runner game targeting touch-screen devices from *low-end_to_bleeding-edge, state-of-the-art* hardware using a mix of *cheap, low-poly animation and art*; and *a clean, oversimplified design*...
> > // leaving as much room as possible for more expensive FX (light, particle, noise in materials/shaders andtextures
...and *equally oversimplified quality settings;* developing in *Unity*.
Set entirely undersea *(infinite-diver then...)*, it will have a female diver character, a theme of isolation in the...*and this can't be overstated*...Pants-Shitting-Vastness (PSV) of the sea.
---
```
[c:dd_the-concept_plan]
```
# the-concept
> // return to for guidance; simplify when possible .
* An undersea IR; a balance of zen and adrenaline; cover-shooter swipe controls; isolated, thlarger-than-life "the ocean wants you dead".
---
```
SECTION TWO - SOUNDING BOARD OF ELEMENTS (NOT-YET-IMPLEMENTED IN DESIGN)
```

```
[c:dd_the-"get-it-all-out-so-you-can-sift-the-diamonds-from-the-riverbed".notes_plan]
```
> // paged by topic; `# notes`, then `## assets` if applicable.

# notes-on-the-art-direction
* I would like the visuals to be of the darker, moodier variety, similar to the visual-noise-driven light-rendering--and low-poly clever-animation-can-create-character-as-much-as-geometry--techniques used in **Playdead's Inside** (thoroughly outlined [here](https://www.youtube.com/watch?v=RdN06E6Xn9E)).
* I would like to apply different noise (and otherwise shader) effects to seperate objects simultaneously. At this time, using the `Screen space - Camera` and locking the camera and/or light configuration--and therefore the effect--onto the desired Object as part of the Prefab, so it'll generate at spawn time, seems like a solution... but wherether it'll work that way is TBD.

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


# the prototype
// heavily oversimplified into what works and what doesn't; brief explanations when deemed absolutely necessary.
```
## prototype-needs
* Which in-editor assets do you want to use during development?
> > // also, wtf does each asset do that you're trying to leverage SPECIFICALLY for this part of this pipeline in this project?
## prototype-assets
## prototype-decisions

// page-sorted by category
```

```
[c:dd_the-2d_plan]
```
# needs
# choices 
---
```
[c:dd_the-art_plan]
// ! moved to it's own .md doc !
```
# needs...
## ...concept-art...
### ...by-hand
> // graph paper; mostly needs too small or specific to be met by third-party assets.
# decisions
---
```
[c:dd_the-agents_plan]
```
# needs
# assets
# decisions
---
```
[c:dd_the-camera_plan]
```
# needs
# assets
# decisions
```
[c:dd._the-controls_plan]
```
# needs
* Swipe-controls  // shooting for similar feel to uppercut's Epoch/Epoch 2 - The User will swipe in whichever direction they need to move to. This mechanic will use what Epoch 1/2 used with cover, but I'll apply this so that the User can move to different `Lanes` to move forward through, both navigating the terrain *(sandbars, coral, rock-formations...eventually twisting caves and chutes, and also confined lanes made from currents and confined by turbulence from `Entities of Water Motion` like Tides, Currents, possibly larger-than-life elements like Maelstroms and Kraken tentacles...that's not too ambitious for a first commercial game, right? (Note: I know it's too ambitious, I'll let this idea go when I'm ready.)*, and interacting with dangerous elements of the environment *(large and predatory fauna, sharp flora, jagged manmade/natural structures)*
# choices
---
---
```
[c:dd_the-learning-daemons_plan]
```
# needs
# decisions
---
```
[c:dd_the-fx_plan]
```
# needs
# decisions
---
```
[c:dd_the-interfaces-(interfi?)_plan]
```
# needs
# decisions
---
```
[cdd:the-levels_plan]
```
# needs...
## ...modules 
# assets
# decisions
```
[c:dd_the-materiails_plan]
```
# needs
# decisions
---
```
-[c:dd_the-maths_plan]
```
# needs...
## ...forward-motion
* The Gravity of--or Force exerted on--the Level `Modules` moving around the User will start with...
> // Assuming a screen of 16x9 Units (common ratio on mobile devices).
  a. baseline speed = ~8-10 u/s	// this is the ~gravity force setting in Unity, yeah?
  b. hindered speed = ~7-8 u/s
  c. boosted speed = ~10-13 u/s
> > // units will probably = meters, but I'll commit to the metric system when I'm emotionally mature enough to let go of my Kraken idea.
# decisions
```
[c:dd_the-meshes_plan]
```
# needs
# decisions
---
```
[c:dd_the-navigation_plan]
```
# needs
# decisions
---
```
[c:dd_the-physics_plan]
```
# needs
# decision
---
```
[c:dd_the-procedural-content-generation_plan]
```
# needs
# decisions
---
```
[c:dd_the-sounds_plan]
```
# needs
## 
# decisions
---
```
[c:dd_the-scripts_plan]
```
# needs
# decisions
---
```
SECTION FOUR - THE PROTOTYPE DEVELOPMENT
```
---
```
SECTION FIVE - THE PREPRODUCTION PLAN
// based on choices made in prototype development.
```
```
[c:dd_the-preproduction_plan]
```
# needs
# assets
# decisions
---
```
SECTION SIX - PRODUCTION PIPELINE [DEVLOG -OR- TRANSCRIPT OF COMPLETED TASKS]
```
```
[c:dd_the-production_pipeline ]
```
# needs
# assets
# decisions
---
```
SECTION SEVEN - THE LEFTOVERS`
```
```
[c:dd_the-leftover-assets-plan]
// the-delicious-leftovers-you'll-heat-up-and-eat-for-lunch-(the-next-project)-tomorrow.
```
# needs
# decisions
