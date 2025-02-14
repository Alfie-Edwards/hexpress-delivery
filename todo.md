# general

* [x] determine theming
* [x] determine list of item types
    * big box: Cauldron
    * little box: Tome
    * fragile: Urn
      - Releases spirit when it breaks
    * 'this way up': Potion bottle
      - Effect when it breaks
        - Smoke
    * explosive: explosive Box
    * pops bubble wrap: sacrificial knife

# graphics assets

* [ ] environmental background
    * [ ] sky
    * [ ] ground
    * [ ] road
    * [ ] objects passing by?
* [ ] frame of the van
* [ ] background of inside the van
    * [ ] Tyres spinning (2 frames?)
    * [ ] Background objects to pass by on the sides
* [ ] items
    * [ ] Urn
    * [ ] Tome
    * [ ] Potion bottle
    * [ ] Box labelled Explosive
    * [ ] Sacrificial Knife
* [ ] character
    * With and without bubble wand:
        * [ ] standing frames
        * [ ] running frames
        * [ ] jumping frames
        * [ ] airhang frame(s)
        * [ ] falling frame(s)
    * [ ] picking up frames?
    * [ ] holding item frames
    * [ ] Bubble blowing
* [ ] Bubble staff
* [ ] Bubble staff station
* [ ] font(s) for in-game ui
    * numeric indicators for how long before item's dropped off
    * score
    * general text: titles, menu items, messages (eg. you lose), other text (tutorials?)

# programming

* [x] frame of the van
* [x] background graphics (inc. turning)
* [x] items that bounce around
    * [x] big box
    * [x] little box
    * [x] fragile : URN
    * [x] 'this way up'
    * [x] explosive
    * [x] health and wrap level
    * [x] damage
* [~] character controller
    * [x] running
    * [x] jumping
    * [x] getting hit by bigger items?
    * [~] picking up/putting down items
    * [x] wrapping items
* [x] wrapping
    * [x] graphics (existing wrappings)
    * [x] graphics (new wrap going around)
    * [x] collisions
* [ ] turning (throwing things around)
    * [ ] any telegraphing (other than ui)
    * [x] throwing things around
* [ ] basic framework
    * [ ] items getting added & dropped off
        * [ ] indicators
        * [x] scripting the sequence of this for a level
    * [ ] lose if item(s) broken
    * [ ] win if get to the end
    * [ ] score
    * [ ] sequence of levels
* [ ] levels
* [x] main menu
* [ ] you lose
* [ ] you win
* [ ] any in-game ui?
    * [ ] upcoming turns
    * [ ] realtime score?
* [ ] tutorial?
    * eg. text boxes telling you how things work

# sound

* [ ] bubble wrap popping
    * small/med/large?
* [ ] game music
    * increasing intensity?
* [ ] driving sounds
    * [ ] engine noise
    * [ ] turning sounds
    * [ ] speed bump sound
* [ ] item breaking sounds
    * [ ] cauldron metallic breaking
    * [ ] book breaking (eg. tearing paper)
    * [ ] potion/urn breaking
    * [ ] spirit being released
        * [ ] spirit wooooo
    * [ ] smoke being released
    * [ ] explosion
* [ ] indicator alarm for when a turn's coming up
* [ ] sound when shooting bubble staff?
* [ ] sound when bubble shot from staff hits something?
    * could have different sounds when the bubble hits the wall, vs. an item,
      vs. popping in the air, but that can be a stretch
