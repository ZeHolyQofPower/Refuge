## What Am I Looking At?
Refuge is a 3D puzzle adventure game. An island to explore, with journal excerpts to discover the lore, and a mysterious door that unlocks with three hidden keys. Our team of three people, [Cole](https://github.com/colelewis), [Kora](https://github.com/KoraLoud), and [I](https://github.com/ZeHolyQofPower), filled the island with realistic beaches, forests, a maze, a tower, a cabin, and various foliage.

This game also has a two minute [trailer](https://www.youtube.com/watch?v=6IcB0dZ5vS0&t=10s) on YouTube.

## Technical Skills Presented

* This project was assembled in Unity 2021.3.11f1 across Windows 10, MacOS, and Pop!_OS 20.04.
* GUI and all 2D assets created in GIMP. Infinitly repeating textures for sand and grass for example:

<img src="https://github.com/ZeHolyQofPower/Refuge/blob/main/Assets/Visual/Pictures/sand.png" width="150" height="150"/>    <img src="https://github.com/ZeHolyQofPower/Refuge/blob/main/Assets/Visual/Pictures/grass.png" width="150" height="150"/>
* 3D models created in Blender. This rat model for example:

<img src="https://github.com/ZeHolyQofPower/Refuge/blob/main/Readme_Assets/rat_jr_model.png" width="300" height="150"/>

* Rigging, weighting, and inverse kinematic animation using keyframes done in Blender.

<img src="https://github.com/ZeHolyQofPower/Refuge/blob/main/Readme_Assets/rat_jr.gif" width="600" height="300"/>

* Movement animations and state logic made using C# scripts in Unity.
* Material effects like transparency, reflections, and bump maps, created in Unity's Shader Engine.

<img src="https://github.com/ZeHolyQofPower/Refuge/blob/main/Readme_Assets/ocean_waves.gif" width="600" height="300"/>

## Soft Skills Presented
* Formed a team of three for the entire semester. This specific game had eight weeks of development.
* Wrote a detailed [Game Design Document](https://github.com/ZeHolyQofPower/Refuge/blob/main/Game%20and%20Technical%20Design%20Document.docx) that planned out the deliverables and unified vision.
* Met in weekly stand up meetings outside of our class time. Also communicated regularly in a Discord server.
* Adjusted our plan and development sprints around professor feedback and other school projects.
* Spent time together in person to solve software interaction problems and merge complex branches.
* Picked up and learned completetly new software tools independent of any instruction.
* Polished complete game, and created trailer at end to present to class!

## Digging Into the Details and Code
Want to really take a look yourself?

The [refuge_build_for_windows.zip](https://github.com/ZeHolyQofPower/Refuge/blob/main/refuge_build_for_windows.zip) is a complete and self contained Windows version. You can download it and play it for yourself.

Unity is a detailed IDE with many included libaries and tools. For visual assets created outside of it and imported, a surprising amount of information on their usage is stored inside their `.meta` files. For behavior defining code, C# scripts are called by a framework of multithreaded "game engines" and "managers". Although this project sticks to a simple set, each can be heavily modified for each game's individual needs. You can examine code in [Assets/Scripts](https://github.com/ZeHolyQofPower/Refuge/tree/main/Assets/Scripts).

To examine the complete scene's organization and the tunable values, installing Unity on a Windows or Mac system is required. Installing and configuring a Linux environment that is able to correctly run Unity's shader engine and development is very challenging. I learned the hard way that Unity's "officially supported" distro and kernel are a bumpy road of installing missing dependencies, manually compiling unofficial libaries, and avoiding specific unstable tools. I got it all to work once for learning purposes, and I learned I'm never trying that again.

For a detailed analysis of the project install [UnityHub](https://unity.com/unity-hub), give them an email for a free personal license, download a 2021.3 version of the Unity editor and this repo, and import and open the project. I am aware this sentence is easier said than done. If you are comitted to trying this and hit an inevitable roadblock, reach out to me via email for IT support.
