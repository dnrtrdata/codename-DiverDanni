# codename-DiverDanni

## the-pitch
**Codename DiverDanni** is a 3D Infinite-Runner game targeting Mobile devices.
It is set entirely undersea *(infinite-diver then...)* and have a female diver character. The game's mood/feel of isolation within--*and this can't be overstated*-the Pants-Shitting-Vastness (PSV) of the sea. Codename Diver Danni will be developed in Unity.

## concepual-notes
I'm excited about this project because it'll give me a venue to play with screen-space controls I haven't-yet seen utilized in the IR genre: I want to use a swipe control-scheme shamelessly stolen from brilliantly addicting (but sadly a bit outdated) cover-shooters [Epoch](https://www.youtube.com/watch?v=nt3vcJmilqU) and [Epoch 2](https://www.youtube.com/watch?v=xkD57QHmTTE) from [Uppercut Games](https://www.uppercut-games.com/). I love these controls. They have been immensely satisfying to me.

I'm also drawing inspiration from the brilliant and beautifully-oversimplified character mechanics and environment creation in [Alto's Adventure](http://altosadventure.com/) and [Alto's Odyssey](http://www.altosodyssey.com/) by [Team Alto](http://www.altosadventure.com/team/)... specifically the one-touch jump/hold-to-backflip mechanic and the masterfully-composed layers of 2D sprites and increment weather. Who knows if I can acheive anything similar, but I'm going to try fleshing out the world's bg visuals with a similar aesthetic.
  Developing in Unity.

## leveraging-screen-space
* I would like the visuals to be of the darker, moodier variety, similar to the visual-noise-driven light-rendering--and low-poly clever-animation-can-create-character-as-much-as-geometry--techniques used in **Playdead's Inside** (thoroughly outlined [here](https://www.youtube.com/watch?v=RdN06E6Xn9E).
* I would like to apply different noise (and otherwise shader) effects to seperate objects simultaneously. At this time, using the `Screen space - Camera` and locking the camera and/or light configuration--and therefore the effect--onto the desired Object as part of the Prefab, so it'll generate at spawn time, seems like a solution... but wherether it'll work that way is TBD.

### User/Agent Screen-space Zones
> // though the game is entirely forward-moving...using the "depth" (or Z-axis), much of the gameplay mechanics will work around using left/right and up/down (X and Y axes, respetively).
### swipe controls

## Infinite-Runner-conventions
### IRC's-to-keep
> // Infinite Runner Conventions I want included
* Forced motion on level `Modules`
> > // wouldn't be an IR if you got to stop and take breathers.

### IRC's-to-lose // Infinite Runner Conventions to exclude

## the-math-so-far:
### forward-motion
*Assuming a screen of **16x9 Units** (common ratio on mobile devices; units will probably = meters, but I'm an American and not yet ready to commit :/ )*
* The Gravity of--or Force exerted on--`User` (actually the `Level Modules` moving around the User) will start with...
  a. baseline speed = ~8-10 u/s
  b. hindered speed = ~7-8 u/s
  c. boosted speed = ~10-13 u/s

## approach-to-modules-and-PGC
This will need to be segmented due to the Assets I may be able to leverage into the process.

## Leveraging-the-Asset-Store
  I've jumped the gun on picking appropriate tools and purchased more Asset Store assets than is probably wise, but they've been having a big sale (ending in ~ 10 hours, I beleive)... so I decided I could justify going a little overboard. There are worse forms of Pandemic retail therapy (see? justifying it EASY).
  If not for use in free-diving game, then for educational use and future products. Anywho, here's a list of Assets I hope to use for this project (very broad; will narrow down with testing).

### Engines
#### *Broad*

### Environmental Tools
#### *Broad*
* **Asset:** Low Poly Water - Builtin & URP - Poseidon 
> // appears simple to use; useful, **scaleable, tileable patterns**; mesh generation choice (plane, area, spline, custom) to **build overhead surfaces, add bg wave FX, and foam to User/Agent locomotion**; add ripples to large creature/structure events that make User feel small and insignificant (PSV).
* **Asset:** 
> // 
#### *Isolated*
* **Asset:** 
> // 
