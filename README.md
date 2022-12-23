# Capstone Proposal   (w/ Research & Planning Log) 

## By Sam Majerus  (File created 12/2/2022)

#### This repo contains my Capstone Proposal and "Research & Planning Log".   

[Link to repo for Unity project](https://github.com/SaMajerus/Leaf-blower-Sim.git) 
<hr/>
<br>


# Research & Planning Log
### Friday, 12/02
* 8:20-8:30:  Research how to duplicate an existing Unity project
* 8:30-9:00:  Create local project folder and files.  Create & format this README. 
* 9:00:  Copy down Proposal template (in 'capstone-proposal.md') 
* 9:15-30:  Create GitHub repo.  Initialize local repo, make inital commit, push to remote repo. 
* 9:30-40:  Adjusted the formatting of this README, made edits. 
* 9:45:  Open Unity editor, export C# Team Week project. 
* 10:00:  Create and open new Unity project (with '3D' template).  
* 10:15:  Import the exported C# Team Week project.   [On break for tea, stretching, ...]
* 11:45:  Searching Unity Asset Store for backpack leaf-blower, leaf/leaves, etc. 
  * 11:53:  Add Free 'hair dryer' asset to "My Assets" [for Unity] 
  * 12:09:  Add free 'simplistic low poly nature' asset pack to "My Assets" 

<!-- * [12:30-13:10:  Added links to job postings I saved yesterday to my Job Tracker, for further evaluation later.]   -->

* 13:40:  Attempt to fix apparent issues/missing assets (i.e. those that were not included in Export package) --
* 14:00:  Copying 'csharpteamweek' project from PlasticSCM workspace directory to UnityHub's ProjectTemplates folder. 
* 14:30:  Attempting to create a new project in Unity Hub using the newly-copied root directory as the template. 
* 14:40:  Deleting failed project attempts,  looking further into process of adding a Custom Template for Unity.   ('csharpteamweek' didn't show up as a Template option.)
* 15:15:  Creating new project file with generic 3D template (since I can't figure out custom templates).  
* 15:20:  Using Package Manager to import select Assets from the two newly-added Asset Packs.  
* 15:25:  Importing the 'csharpteamweek' project's package.  
* 15:30:  Saved the project, closing Unity Editor. (Import of the Team Week project's exported package was successful.)   [Updating activity log] 
* 15:45:  Beginning work on Capstone Proposal. 
* 16:45:  Pushing this entry and the Proposal document to remote repo.  
<br><br>



### Friday, 12/09
* 10:05:  Researching how to start/add my own PlasticSCM repo (for Source Control) for the Project. 
<!-- * 10:30:  Researching how to change the gameplay environment without accidentally interfering with the player's current HUD and Menu scenes.  -->
* 10:30:  Figuring out how to edit Scripts in VS Code. 
* 10:45:  Determining next steps
* 11:15:  Start re-familiarizing myself with the C# code from Team-Week project 
* 11:40:  Figure out how to replace 'keyboard-gun' asset/object with Hair-dryer asset/object.  (While keeping the same scripts, at least initially.)
  * 11:55:  Continuing above investigation in Unity Editor instead of VS Code (for now) 
* 12:10:  Remaking Unity project (due to root folder naming issue that prevents me from navigating back to it in Cmd-Line).
* 13:00:  Lunch break

* 14:15:  Initializing/setting up Local and Remote Git repos (with '.gitignore' imported from Team-Week project) for the Unity project. 
* 14:40:  Continuing task from 1140. 
<!-- * 15:15:  Slight detour to finish -- and submit -- first of two job applications. -->
* 15:45:  Continuing task from 1140. 
* 16:25:  The Hair-dryer -- I mean, Leaf-blower -- is now positioned so that it's on-top-of/clipping-into the Keyboard-gun's location in space (in the player's virtual hands).    [WIP:   task from 1140, part 2; switch out Keyboard object with the Hair-dryer, keeping the existing scripts (applied to the object) as they are for now.]
<br><br>



### Tuesday, 12/13 
* 14:45:  Exploring Hierarchy of Game Scene, comparing/contrasting Hairdryer Asset's components with that of the ''Keyboard-gun''.   
* 15:38:  Looked up the definition of 'LOD' in the context of Unity 3D. [It's short for 'Level of Detail'.]   
* 15:40-16:30:  (Same as 1445.) 

* 16:35:  Doing more research on how I can swap one Asset for another in Unity (without having to re-attach Scripts/other components to the new Asset.) 
* 16:45:  Reached out to Skylan  (teammate from the C# Team-Week project)  for tips/suggestions/help on how to proceed with Asset swapping  [especially given how we structured our 'Player' prefab hierarchy-wise in that project].  
* 17:10:  Searched Asset Store for Free particle effects (i.e. Wind/breeze effects) and/or physics "materials" (i.e. 'block' of air, blast of air, air/wind gust effects and/or physics, ''parcel of air'').  
  - Even after 8 minutes of searching intently, I found nothing that matching what I want. 
    * There <em>was</em> a "Low Poly Wind Effects" package, <em>but</em> it costs $15, which is ridiculous!    (If I can't manage to improvise with the 3D Physics that Unity provides by default, <em>I guess</em> I'll buy it.) 
<br><br>



### Wednesday, 12/14 
* 10:30:  Doing Log entry for 12/13 (since I forgot to yesterday). 
<!-- * 11:10:  Formatting edits in this document.  -->
* 11:30:  Attaching components (which were attached to the Keyboard when I deleted it) to 'Hairdryer' object/Asset. 
  -Yesterday, before deleting the Keyboard object, I went through and took screenshots of the components attached to it. (This ensures that I know exactly what to attach to the Hairdryer object/Asset.)  
<!-- * 11:55:  (Went to Lunch.) -->
<br><br>



### Friday, 12/16
* 9:45-10:00:   Researching how to set/change physical size attributes of an Asset/Game-Object in Unity 3D editor. 
  - I want to take the length of the Hairdryer's main body and stretch/increase it by a factor of 1.5.  (Then it'll at least resemble an actual Leaf-blower's tube.)  
<!-- * 10:15-30:   Following along with tutorial I found.  (Link: https://www.youtube.com/watch?v=XZnmMGz_VyU)  -->
* 10:30-11:20:   Comparing sizes of my IRL Leafblower's tube-assembly with that of an IRL hairdryer.  (The dryer that I'm using for this comparison of sizes is [in my estimation] approximately-equal to the size of the GameObject's real-life counterpart.)  
  - Notes--  
    * Hairdryer (IRL): 
      - Full tube/body length=  7.5in 
      - Length from nozzle-end to back-of-handle=  6.0in 
      <!-- - Nozzle diameter=  2.25in.  (4.5in-long taper down from (the widest-point's) 3.75in diameter.)  -->
    * Leafblower (IRL): 
      - Full tube length=  34in 
      - Length from nozzle-end to back-of-handle=  27in 
      <!-- - Nozzle diameter=  2.75in.  (2.75in-long taper down from 3.75in (tube-) diameter.)  -->
    * 34/7.5 ~= 27/6 ~= 4.5   
      - [(Either of the Hairdryer's length values) x 4.5  ~=  (Corresponding length value for IRL-leafblower)].

<!-- * 15:05:   Continuing to follow along with tutorial  (taking into account the measurements noted above).   -->
* 15:35:   Just discovered that the technique used in the tutorial no longer works.   (Doing further research on an alternative.)

* 15:50:   Turns out that changing the scale of the object from the Inspector window does what I want (in this case). 
* 15:55:   Fiddling with GameObject/Asset Scale values, (and trying to not have the texture turn black again, if at all possible).  

* 16:00:   Modification of basic Hairdryer to be longer (using Scale property) is complete!  
<br><br>



### Monday, 12/19
* 11:20:   Researching how to implement/apply Physics effects (in general) to GameObjects. 

* 15:00:   Adjust existing elements to create 'ground' surface of game, disable 'Enemy Spawner' for now. 
* 15:40:   Add a Leaf prefab, begin experimenting with Physics. 
* 15:45:   Attempting to refresh myself on making a global 'csproj' or 'json' file(??) to hopefully fix the build errors.... (Have to accomplish this <em>before</em> I can proceed with anything else, preferably.)
<br><br>



### Tuesday, 12/20
* 9:15:    Seeing if building the Unity project (as it is now) is successful.  [Also want to see if a global 'csproj' or 'json' file gets created as a result (and if so, whether or not the dotnet commands work normally).] 
<!-- * 10:35:   (Partially figured out the whole 'global project-file creation for Unity 3D project (with C# scripts)' thing... I guess...  Putting on back burner for now.) -->

* 10:45:   Starting work on object(s) for "Leaf demo".   
  - Will experiment/test/fiddle with physics -- and reference tutorials -- as needed. 
* 11:10:   Experimenting with Rigid-bodies, Colliders, et al.  
* 11:25:   Investigating why the Character slides slowly in X-direction (20 seconds(?) in) without any inputs.... 
  -No player-movement inputs stop it.  
  -At least the collider/Mesh-collider(?) on Leaf object works -- the player can push the leaf by bumping into it. 
* 11:40:   Turns out that the cube object (a.k.a. the floor) is continuously moving in the positive-X direction  (even though movement in the X/Y/Z directions <em>should</em> be disabled/frozen).  

* 11:55:   Breaking for Lunch
  -Will try to fix the Floor's "illegal +x-direction movement(?)" first thing afterwards.   


* 14:20:   Resuming work. 
* 14:35:   Issue I came across earlier (around lunchtime) is fixed.  (The Cube/Floor is now a Static object.)  
* 14:55:   Investigating multitude of errors from 'TEST.cs' file.
* 15:00:   Fixing errors, making changes to files as needed. 
* 16:10:   Committing and pushing latest refactorings of Gun.cs, et al. (More of those to come.) 
* 16:30:   Investigating if particles from a particle system can exert Force on a GameObject.  (Also, how to link a Callback function(?) to stopping the particle simulation -- in other words, toggling it On/Off.)
<br><br>



### Wednesday, 12/21
* 8:15:   Researching and watching Unity tutorials relevant to the work I expect to be doing today. (Links listed below in order of discovery [first two are from yesterday].) 
  - [How to Create Physics in Unity | Rigidbody and Colliders in Unity](https://www.youtube.com/watch?v=7LVOeNalTFA) 
  - [Unity3D Physics - Rigidbodies, Colliders, Triggers](https://www.youtube.com/watch?v=dLYTwDQmjdo) 
  - [Everything to know about the Particle System](https://www.youtube.com/watch?v=FEA1wTMJAR0) 
  <!-- - [Unity Shortcuts you NEED to know!](https://www.youtube.com/watch?v=yMqefz8XNC4) -->
  - [FIRST PERSON MOVEMENT in Unity - FPS Controller](https://www.youtube.com/watch?v=_QajrabyTJc)
  - [Shooting with Raycasts - Unity Tutorial](https://www.youtube.com/watch?v=THnivyG0Mvo)
  - [THIRD PERSON MOVEMENT in Unity](https://www.youtube.com/watch?v=4HpC--2iowE)

* 10:00:   Following along with the '1st-person Movement' tutorial in Editor.  (For science) 
* 10:50:   Refactoring scripts/properties/etc carried over from the C# Team Week project.  (I've also stopped watching the tutorial -- probably won't implement that approach for MVP.) 

* 11:40:   (Break)
* 13:15:   Resuming work on refactoring.  (See entry at 1050 for more info) 
* 15:40:   (Break)
* 15:55:   Resuming. 
* 16:45:   Saving work and logging out of Epicenter. 
* 21:00:   Opening Unity project to compile the C# scripts (and thus automatically change the associated '.cs.meta' script files). 
* 21:12:   Fixing compilation errors reported by Unity Editor (opened in Safe Mode), then pushing all changes to GitHub. 
* 21:35:   Submitting bug report after Unity Editor crashed in Safe Mode (while it was attempting to restore Scenes? -- "Reload Script Assemblies" got done, but weren't saved automatically due to the crash occurring during that process, potentially). 
* 21:50:   Push the Script file changes to GitHub. (Continuing to diagnose/attempt to fix it.) 
* 22:20:   Skylan suggested moving the Scene [that I last had open] out of the project's directories, then trying to open the Editor after that. (If it works, I'll just have to recreate the scene.)
* 22:35:   It worked!  Pushing all changes to GitHub, then calling it for the night. 
<br><br>



### Thursday, 12/22
* 8:40:   Recreating gameplay Scene.
* 8:55:   Working on implementing projectile/particle-system physics so the Blower can blow/launch the Leaf object. 
  - 9:00:   Adding Leaf prefab under a different name -- 'Leaf_demo' -- under the 'Assets/Prefabs/' directory. (Replaced the default prefab (from the Simple Nature pack) in the Scene hierarchy with this. Made sure that both the preset Position and Scale values are saved as part of the Prefab.)
  - 10:15:   [Break to get breakfast]
  - 10:35:   Review how this statement from the base project works, and research how I can best refactor it for my 'Idle' function (Blower.cs, Ln 119):  'yield return new WaitForSeconds(reloadTime)'. 
  - 11:00:   Beginning research on the 'yield' keyword in earnest -- (no one from the C# Team-Week project remembers how the 'yield' keyword works in a return statement).    Also researching how to script (if needed) the physics interaction between the Blower and Leaf objects. 
  - 12:50:   Adds Raycast physics for blower. (Guided by the top help-answer found here:  https://answers.unity.com/questions/1027665/need-help-applying-force-to-objects-hit-by-raycast.html .) 
  - 13:00:   Testing aforementioned additions real quick before breaking for a quick lunch. 
* 13:15:   [Break for quick lunch]. (Will continue trying to test afterwards.) 

* 13:20:   Continuing to try and get the Raycasting physics to work. 
* 13:30:   Joining Google Meet for Capstone Presentations. (Will continue to work on this in background, here and there.) 
* 15:00:   Idea for future exploration -- shoot an invisible projectile object at target. (Have projectile despawn after delivering Force)
* 15:10:   Just discovered that the Physics were not being applied because the Blower object was not itself a Prefab in the Player Prefab. (Physics are now applied.. except the player moves instead of the leaf (or something)...) 
* 15:20:   Created build folder for initial (albeit very-WIP) iteration of game. 

<br><br>



### Friday, 12/23
* 9:25:   Still can't push build folder to GitHub without getting the following (at 'Writing [ objects ] = 76%):  "error: RPC failed; curl 92 HTTP/2 stream 0 was not closed cleanly: CANCEL (err 8)
send-pack: unexpected disconnect while reading sideband packet
Writing objects: 100% (183/183), 174.41 MiB | 9.74 MiB/s, done.
Total 183 (delta 66), reused 0 (delta 0), pack-reused 0
fatal: the remote end hung up unexpectedly". 

* 9:30:   Researching character movement using Rigidbody approach. (If I can at least get the character's movement inputs to work properly, then I can take that one item off my plate.) 
* 9:55:   Removed the last 5 commits (4 of which were problematic and caused failed Pushes to GitHub in all 5 cases) from the Leaf-blowing-Sim project's log. (Used the command 'git reset --hard HEAD~5'.)
  - Link to article/page that provided this solution:   https://gist.github.com/CrookedNumber/8964442 
* 10:00:   Re-committing the one [under normal conditions] non-problematic commit for the Unity project. (Contains two copied READMEs, each from one of my other projects, so that I can craft a suitable README for 'Leaf-blowing-Sim'.) 
* 10:20:   (Break to get breakfast proper) 
* 10:30:   Continuing "Research character movement using Rigidbody approach" task. 








<!-- [Example entry]
* 1:20: implement react-spring library in sample project 
-->








<!--
<br><br>
<hr/>



## License
Email me at ladolego@gmail.com for questions, ideas, concerns, or even any issues that you run into. !--You may also clone or Fork the content in this Repo to fiddle around with it, if you like.--

Licensed through MIT. Copyright (c) 12/2/2022, Samuel Majerus. --> 