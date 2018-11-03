---

# MINE LITTLE PONY

## SKIN PACKS REPOSITORY

---

* Show-accurate colours and updated pony naming kindly provided by the MLPVector-Club https://mlpvector.club/

* This pack is provided as a free-to-use, free-to-distribute fan creation.
  All properties belong to their respective owners.

https://minelittlepony-mod.com/

## NOTES

If your skin is included in this pack, it will have been tweaked slightly
(changing the eyes and hooves) to fit in with the rest of the pack. 
It is encouraged that contributors try to keep it as consistent as possible.

The two eyestyles here are:

Adults - Alpha's Style
Foals  - Steph's Style

If you would like to submit a skin, go to the minelittlepony.com forums
and then head over to the "Canon Skins for the mod" bit of the forum 
and make a new topic including a picture of the skin and the skin itself.

## RESOURCE PACKS

This pack serves a double purpose as an example to resourcepack authors. The skins in this pack
are broken down into a number of smaller categories, each arranged into their own folder.

Background Ponies 	- are the textures already included and used throughout the mod by default
Main Cast						- primary and supporting characters from the show
Villains						- evil
Special Event				- Once-off, single event skins from the show and related events
Minecraft						- Minecraft mobs and entities (humanoid) created specifically for
											Mine Little Pony

Alternative Outfits - Any additional costumes and get-ups of skins included in the other
											categories. The 'Other' skins
											
Each category on its own is designed to work as a drop-in replacement for the background ponies
already included with the mod. They have their own bgponies.json listing all of the ponies
included.

Custom packs can be created by adding skins to the respective folder and editing the
bgponies.json according to instructions at the top of the file.

The normal (v1) format Mine Little Pony resourcepacks appears as thus:

Mod assets structure:

    assets / minelittlepony /
	lang /
		...lang
	textures /
		cubemap /																- Panoramas
			quillsandsofas_<n>.png
			sugarcubecorner_<n>.png
			sweetappleacres_<n>.png
		entity /
			enderman / 														- Enderstallion textures
			illager /															- Illagerpony and Vex texture	
			
			pony /														<- Background ponies go here
				bgponies.json
				<pony textures>
				
			skeleton /														- Skeleton/Wither Skeleton/Stray textures
			villager /														- Villager textures
				...
				silly_pony.png											- Shhhhh a secret
				tiny_silly_pony.png									- ditto
			zombie /															- Zombie/Zombie Pigman/Husk textures
			zombie_villager /											- Zombie Villager textures
			alex_pony.png													- Used for the slim arms models.
																								See "Background Ponies/Night Guard (Bat)"
			seapony.png														- Guardian/Elder Guardian texture
			steve_pony.png												- used for the fat arms model.
																								See "Background Ponies/Daring Do"
			witch_pony.png												- The witch texture. (hat comes from vanilla)
																								See "Background Ponies/Zecora"
		mob /
			noskin.png														- Blank (steve) skin for the skins gui
			noskin_seapony.png										- Seapony variant
		models /
			muffin.png														- The muffin hat texture
			stetson.png														- Applejack's hat texture
			armor /																- Vanilla and mod armour textures.
				<armour-type>_layer_inner_pony.png
				<armour-type>_layer_outer_pony.png
