### Ki-Cad Libraries Used in Projects

To use this libraries with 3d models loaded you should do the following steps:

	1. Clone this repository in a directory **recursively**.
	
	2. Go to `Prefrences` -> `Configure Paths...`, and add the path of directory under the name of `THISPTR_LBR_DIR`
	
	3. Now you can add libraries to the kicad library manager and use it. You should add the `*.kicad_sym` file to the Component Libraries: 
		`eeschema:Preferences->Component Libraries->Add`

	4. Add `*.pretty` to the Footprint Libraries: 
		`pcbnew:Preferences->Footprint Libraries Wizard`
