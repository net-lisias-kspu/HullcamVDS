# Hullcam VDS /L Unofficial :: Change Log

* 2014-1013: 0.32 (Albert_VDS) for KSP 0.25
		- Compiled against 0.25
* 2014-0907: 0.31 (Albert_VDS) for KSP 0.24.2
	+ Compiled against 0.24.2
* 2014-0823: 0.3 (Albert_VDS) for KSP 0.23.5
	+ No changelog provided
* 2014-0507: 0.2.9.5 (Albert_VDS) for KSP 0.23.5
	+ No changelog provided
* 2014-0421: 0.2.9.2 (Alvert_VDS) for KSP 0.23.5
	+ fixed a bug which accidentally slipped in 0.2.9.1
	+ Source code available as zip file.
* 2014-0420: 0.2.9.1 (Alvert_VDS) for KSP 0.23.5
	+ Compiled against 0.23.5
* 2013-1030: 0.2.9 (Albert_VDS) for KSP 0.7.3
	+ Added the new camera science module, from L-tech Science, to every camera.
	+ Added the following new cameras made by Rubber Ducky:
	+ Launchpad camera - made for being set up around the launchpad for great
	+ ScienceCam - just a basic all-purpose camera
	+ NavCam - tiny with a wide FOV, mainly for piloting rovers. Has a static-y overlay built into the model.
	+ BoosterCam - a variation of aerocam; two cameras built in, facing up and down.
* 2013-1018: 0.2.8 (Albert_VDS) for KSP 0.7.3
	+ Small compatibility update
* 2013-1027: 0.2.7.1 (Albert_VDS) for KSP 0.7.3
	+ Added support for the [L-Tech Scientific Stuff mod](http://forum.kerbalspaceprogram.com/threads/53813-0-22-L-Tech-Scientific-Stuff-V1-5)
* 2013-1025: 0.2.7 (Albert_VDS) for KSP 0.7.3
	+ Map bug fixed by a.g. (skybox bug remains)
	+ Added all parts to the tech tree.
	+ Added Ordan Industries Telescopes(with permission of hubbazoot and added them to Unmanned Tech.
	+ Added part Basic Hullcam Deluxe and to Science Tech.
	+ Added Aerocams to Aerodynamic Systems
	+ Added Kerbpro to Field Science
	* **No binary available**
* 2013-0915: 0.2.5 (Alvert_VDS) for KSP 0.7.3
	+ Made the keys configurable using the same config syntax as the game itself. The included config file is the one I made for dvorak, while the default without any config replicates the original behavior. The config can be dropped anywhere in GameData.
	+ Added a check that the current camera is flight, using a CameraManager
	+ object referenced in e.g. SteamGauges code. This lets it interact nicely with stuff like IVA views.
	+ Fixed unreliable action of next/prev keys. The problem was using "-=" instead of "&= ~" to remove a bit.
	+ Try to replace the map view hack with manually saving and restoring a couple more properties. It seems to work, although I can only guess at the full purpose of the map view hack.
	+ Glitchy switching between multiple cameras with next/prev keys because they all tried to handle the key.
	+ Crash if exiting to space center while a camera is active.
	+ Changed "next camera" and "previous camera" keys to - and = (Minus and Equals)
	+ Changed "exit hullcam view" key to Backspace.
	+ Added areocam180 part, which has a 180 rotated camera view.
	+ Tweak the areaocam and areocam180 field of view.
* 2013-0910: 0.2.1 (Albert_VDS) for KSP 0.7.3
	+ Added aerocam, an aerodynamic side mounted camera.
* 2013-0823: 0.2 (Alvert_VDS) for KSP 0.7.3
	+ Changed cycle keys to O and P
	+ Pressing V will exit hullcam view
	+ Added KerbPro Camera (created by sirkut)
* 2013-0816: 0.1 (Albert_VDS) for KSP 0.7.3
	+ Made Mechjeb hullcam into a single hullcam.dll
	+ Fixed camera bug when returning to VAB/SPH.