# HullcamVDS /L Unofficial

An interface to control both the Blizzy Toolbar and the stock Toolbar without having to code for each one. Unofficial fork by Lisias.


## Installation Instructions

To install, place the GameData folder inside your Kerbal Space Program folder. Optionally, you can also do the same for the PluginData (be careful to do not overwrite your custom settings):

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
	+ Delete `<KSP_ROOT>/GameData/HullCameraVDS`
* Extract the package's `GameData` folder into your KSP's root:
	+ `<PACKAGE>/GameData` --> `<KSP_ROOT>/GameData`
* Extract the package's `PluginData` folder (if available) into your KSP's root, taking precautions to do not overwrite your custom settings if this is not what you want to.
	+ `<PACKAGE>/PluginData` --> `<KSP_ROOT>/PluginData`
	+ You can safely ignore this step if you already had installed it previously and didn't deleted your custom configurable files.

The following file layout must be present after installation:

```
<KSP_ROOT>
	[GameData]
		[HullCameraVDS]
			[MM_Scripts]
				kerbalEVA.cfg
				...
			[Parts]
				[hullcam_hubbazoot]
					...
				[hc_wideangle]
					...
				...
			[PluginData]
				defaults.cfg
			[Resources]
				shaders.bundle
				...
			[Textures]
				[High]
					...
				[Low]
					...
				[Medium]
					...
				Dust.png
				...
			CHANGE_LOG.md
			LICENSE
			NOTICE
			ToolbarControl.dll
			...
		000_KSPe.dll
		...
	[PluginData]
		[HullCameraVDS] <not present until you run it for the fist time>
			user.cfg 
	KSP.log
	PartDatabase.cfg
	...
```


### Dependencies

* [KSP API Extensions/L](https://github.com/net-lisias-ksp/KSPAPIExtensions) 2.1 or later
	+ Hard Dependency - Plugin will not work without it.
	+ Not Included

