### Sam Majerus

### Leaf-blowing Simulator

### Project's Purpose or Goal: (What will it do for users?)
The player can get an idea for how leaf-blowing works, so that the learning curve is easier when they start using one in real-life. (Basically, provide an environment that is at least semi-realistic compared to real-life, so that prospective first-time users have a sort of reference point for learning.)


#### List the absolute minimum features the project requires to meet this purpose or goal: 
* Working leafblower physics -- can blow objects around. 
* Player can move around. 
* Player can use "Leaf-Blower" on objects, and have those objects respond accordingly with some realism (e.g. simple physics) 


#### What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific. 
* C#
* Unity Editor
* online tutorials for Unity 3D (i.e. for object physics, scripting, etc)
* GitHub for version control 
* (Other technologies utilized by the C# Team Week project that I'm forgetting currently)


#### If you finish developing the [minimum viable product (MVP)](https://www.learnhowtoprogram.com/react/functional-programming-with-javascript/capstone-planning-the-minimum-viable-product) with time to spare, what will you work on next? Describe these features here: Be specific. 
* Advanced leaf-blower output-air physics (so that it's closer to real-life) 
  - When idling, a blower still outputs enough air to cause some things to move, so ideally I'd like to model that too. 
  - Apply more force the closer the target object is to the Blower.
* sound bytes (idling engine, full-blast, varying-levels of power, air-object interaction sounds. Startup/shut-down sounds.   Rustling leaves.)
* Add keybinds that allow one to vary the power settings. (In other words, vary how much force the output-air is applying to target objects.) 
* Add keybinds so that the player can pivot/move the nozzle 30-45 degrees Left or Right in a frontal arc, whilst still being able to move around.  
* Add a fuel system -- show how much fuel the blower has left (we'll assume it's in arbitrary Units for now, instead of Gallons/etc). 
  - Based on this, the player can choose what Level of Difficulty they want to play on for a given scenario.  (I haven't a clue about what to call each difficulty level between the Extremes of the the Arcade-vs-Realism range/spectrum, nor how many in-betweens I want to have.  I do know, though, what I want to have for both Extremes of that spectrum:   'Arcade' gives the player unlimited "Full-Tank Refuel" power-up charges, while 'Full-Realistic' has the Real-Life "fuel capacity"/"fuel consumption at a given power output"/etc characteristics of the Blower, and no "Full-Tank Refuel" power-up charges.) 
    - All fuel characteristic values are to be based on the Stihl BR 600 blower. 
* Create a player HUD (and/or UI) that shows where the nozzle is located in the frontal arc, currently-selected amount of blowing power, etc. 
  - Add a marked zone that the player must blow the leaves into in order to score points and/or win.   


#### What additional tools, frameworks, libraries, APIs, or other resources will these additional features require? 
* Recordings of Blower I have at home, at different power settings.  (with iPhone -- probably using Voice Memos app)
* Any-/Every-thing else:  TBD [To Be Determined]


#### Is there anything else you'd like your instructor to know? 
Couldn't find a Leaf-blower asset, so I'm improvising with a hair-dryer. 
