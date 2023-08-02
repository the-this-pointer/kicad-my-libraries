# Ki-Cad Libraries Used in Projects

How To Use
---------
To use this libraries with 3d models loaded you should do the following steps:

	1. Clone this repository in a directory **recursively**.
	
	2. Go to `Prefrences` -> `Configure Paths...`, and add the path of directory under the name of `THISPTR_LBR_DIR`
	
	3. Now you can add libraries to the kicad library manager and use it. You should add the `*.kicad_sym` file to the Component Libraries: 
		`eeschema:Preferences->Component Libraries->Add`

	4. Add `*.pretty` to the Footprint Libraries: 
		`pcbnew:Preferences->Footprint Libraries Wizard`


Kicad StepUp Mod
---------
Kicad StepUp Mod doesn't support loading 3d models with variables in path by itself. You should either assign the path of the cloned repository to one of the alternative paths in the mod's preferences window, or use [this fork](https://github.com/the-this-pointer/kicadStepUpMod) of the mod and add a named path in the preferences again, To add a named path you should enter the path in the following format: `THISPTR_LBR_DIR@<Clonned Repository Path>`.
