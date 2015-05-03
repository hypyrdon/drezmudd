UI screens
made of panels/widgets
game_screen
	player stat panel
	map panel
	viewport panel
	ref panel (details about what is "seen"/examined/remembered, quest log, char history, ...
debug screen
	debug_detail (of object with focus.  like the ref panel but has debug info in it)
editor screen
	for editing a "thing"  probably different panels depending on what is being edited
		EG: topo editor, critter editor, item editor, ...

world object:
	name, (generic name, possibly calc'd from type, size, equip/trappings, etc..)
	proper_name (the given name of a thing: "shroud of turin", "Gesalt of Durin")
	uuid, the internal ID of a thing (internal-only)
	render_data: this can be 1 or more of:
		ascii/utf8 character 
		utf16 character 
		utf24/32 character 
		icon or other sprite/glyph 2d non-animated graphic
		animated icon/scprite/glyph 2d animated graphic
		3d model(animated or not.  meshes textures, etc... )
	type - critter, feature(furniture,plants,haybail,etc)
	lore

