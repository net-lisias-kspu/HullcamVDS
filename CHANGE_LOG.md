# Hullcam VDS /L Unofficial :: Change Log

* 2018-0901: 0.1.9.5 (linuxgurugamer) for KSP 1.4.5
	+ fixed RPM patch for showing camera fov in the editor for the Kazzelblad and wide-angle camera
* 2018-0901: 0.1.9.4 (linuxgurugamer) for KSP 1.4.5
	+ Fixed error: Texture 'HullCameraVDS/Parts/hc_wideangle/model000' not found
* 2018-0511: 0.1.9.3 (linuxgurugamer) for KSP 1.4.3
	+ Added message to identify current camera when switching
	+ Added two new config options, both defaulting to true:
		- DisplayCameraNameWhenSwitching
		- DisplayVesselNameWhenSwitching
	+ Added new config option, defaulting to 3 seconds, allowable range is 1-10
		- MessageDuration
	+ Commented out all old references to HullCamera and RESOURCE in the parts
* 2018-0422: 0.1.9.2 (linuxgurugamer) for KSP 1.4.2
	+ Fixed shaders, thanks to @Kerbas_ad_astra
* 2018-0418: 0.1.9.1 (linuxgurugamer) for KSP 1.4.2
	+ Disabled log spam due to missing shader
	+ Updated version file
* 2018-0320: 0.1.9 (linuxgurugamer) for KSP 1.4.1
	+ Added change suggested by forum user @jebs_sy to have the camera focus on the vessel (center of mass) instead of a part when leaving the hull camera
	+ Updated for 1.4.1
* 2017-1009: 0.1.8 (linuxgurugamer) for KSP 1.3.1
	+ Updated for KSP 1.3.1
* 2017-0612: 0.1.7.1 (linuxgurugamer) for KSP 1.3.0
	+ Removed log spam
* 2017-0530: 0.1.7 (linuxgurugamer) for KSP 1.3.0
	+ Updated for 1.3
* 2016-1117: 0.1.6 (linuxgurugamer) for KSP 1.2.2
	+ Updated shaders code for windows, now supports both DirectX and OpenGL
* 2016-1113: 0.1.5 (linuxgurugamer) for KSP 1.2.1
	+ Updated shaders for Linux and OSX
* 2016-1103: 0.1.4.1 (linuxgurugamer) for KSP 1.2.1
	+ No changelog provided
* 2016-1103: 0.1.4 (linuxgurugamer) for KSP 1.2
	+ Updated patches to use AFTER instead of FINAL per Sarbian's note
* 2016-1030: 0.1.3 (linuxgurugamer) for KSP 1.2
```
Copied patch from RPM 
Fixed patches for cameras in RPM
Fixed Telescopes
Fixed various offsets and rotations
fixed names in files, so that L-Tech will now have the same camera name as Hullcam
Got all cameras working with RP
```
* 2016-1027: 0.1.2.2 (linuxgurugamer) for KSP 1.2
	+ No changelog provided
* 2016-1026: 0.1.2.1 (linuxgurugamer) for KSP 1.2
	+ Removed extra MM dll
* 2016-1025: 0.1.2 (linuxgurugamer) for KSP 1.2
	+ Release for 1.2
	+ Thanks to @ser for some help
* 2016-0809: 0.1.1 (linuxgurugamer) for KSP 1.1.3
	+ Updated part cfg
* 2016-0807: 0.1.0.1 (linuxgurugamer) for KSP 1.1.3
	+ Initial release
* 2016-0807: 0.1.0 (linuxgurugamer) for KSP 1.1.3
	+ No changelog provided
* 2016-0331: 0.52 (Albert_VDS) for KSP 0.7.3
	+ Test version for 1.1
* 2015-1111: 0.51 (Albert_VDS) for KSP 0.7.3
	+ Compiled against 1.0.5
* 2015-0809: 0.50 (Albert_VDS) for KSP 0.7.3
	+ V0.50 10-Aug-2015
			- Added a modified version of bernierm's MovieTime.
			- Added docking camera, filters and target readouts to all docking ports.
			- Added new camera: "Kazzelblad 500". This camera uses a black and white
	+ filter.
			- Added new camera: "NightVisionCam". This camera uses a night vision filter.
			- Added black and white filter to "Basic Hull Camera Deluxe".
			- Added grainy color TV filter to "BoosterCam".
			- Rearranged of every camera in the tech tree. It starts of with black and
	+ white and better camera's can be unlocked later on.
			- Fixed camera from starting in max zoom. Camera's now start at minimum zoom.
			- Fixed cycle buttons "-" and "+", cycling to the main camera works now as
	+ intended.
			- Fixed bug where the main camera would get stuck if a non-current vessel
	+ camera it got passed 2.5km. Camera will now exit to the main camera if before
	+ it's 2.5km away.
			- Fixed a loading bug which would break cycling to a camera.
			- Other small fixes.
* 2015-0508: 0.40 (Albert_VDS) for KSP 0.7.3
	+ No changelog provided
* 2015-0501: 0.34.1 (Albert_VDS) for KSP 0.7.3
	+ No changelog provided
* 2015-0429: 0.34 (Albert_VDS) for KSP 0.7.3
	+ No changelog provided
* 2014-1217: 0.33 (Albert_VDS) for KSP 0.7.3
	+ No changelog provided
* 2014-1013: 0.32 (Albert_VDS) for KSP 0.25
	+ Compiled against 0.25
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