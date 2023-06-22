
# (Outbreak Equestria) Modding Enviornment 

This repository contains the original tilesheets, tile definitions, building tmx files, wordzed radio data, and configuration for the Project Zomboid mod "Outbreak Equestria" which is currently under development. 

This template is intended to be used by anyone, and everyone who would like to make a contribution to the project. 


## Installation

1. ## Install the Tiles
 The Equestria Tiles folder contains all of the tile definitions, as well as the source images for the tilesets. The source tilesets can be found inside of the Equestria Tiles/2x . They will all have names along the lines of:
```bash
"ponyville_tileset_01.png". 
```

Take all of these .png images, and make copies of them inside of the standard Project zomboid Tiles/2x folder.
[If you don't have the standard project zomboid tiles, you can download them here](https://www.dropbox.com/s/dnirnjphryhtc8w/Tiles-Apr-17-2021.zip?dl=0).

I will push to this repo with the most current versions of the tilsets as I add more. 

3. ## Install the Config 

This next step is *very important*. BuildingTiles.txt, and other configuration files are what tells TileZed which tiles can be used as walls, roofs, floors etc. Having them handy will save you time and effort. 

Simply take all of the files inside of config, and move them into Project Zomboid Modding tools config folder on your own machine. 
```bash
  npm install my-project
  cd my-project
```


4. ## Working With Custom Radio Data

Inside of the Wordzed folder there is a file called "Equestria_Radio.xml". It contains all of the customized radio data. To edit it, you need to import it into Wordzed. If you don't have Wordzed you can [download it here](https://drive.google.com/file/d/1vY-08QJBIzh8gxzIzhGuyLs-RP-CV2T3/view)

After you have extracted Wordzed, I would reccomend placing it into the same folder as the rest of the Project Zomboid Modding Tools. 

Take "Equestria_Radio.xml", and move it to: 

```bash
WordZed/projects/saves
```

Alternativley, you can choose to import it inside of WordZed as part of a new project and skip this step entierly. 


## That's It, You're ready! 

    
