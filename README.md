unmappedtwo
===========

Total rewrite of a plain-text RPG at http://code.google.com/p/unmapped/ which was itself a Darklands-like. Unmapped Two will be even more of a Darklands-like in some ways.

Current thoughts on possible improvements over Unmapped 1:

* Combat model was too complex, thus making it difficult to create a variety of enemies or special effects
* Too much boilerplate code to switch between scenes - the engine should be much more powerful this time
* Need to make sure that multi-line character descriptions are in this time

New features:
* New interface - this means a mouse-driven UI with a lot more possibilities, and no more worrying about text wrapping issues. I had originally been working on doing the UI in Swing, but I realized that Swing really sucks for doing proper layout in, so I'm thinking of alternatives...
* Time - although this will require a lot more scene writing. Darklands had an incredible amount of work put into every scene.
* Character creation involves a more Darklands-like career system after all of the background details are done.
* There will be a single big party inventory of unlimited size (gonna need to work some JScrollPane magic here), and characters equip & use items directly from it
* Whole party temporary effects? Would help the Holy Book system be an even more complete replacement of Darklands' Roman Catholic Saints system.
* Alchemy will get implemented this time
