# WorkAdventure Map Starter Kit

This is a starter kit to help you build your own map for [WorkAdventure](https://workadventu.re).

## Tools you will need

In order to build your own map for WorkAdventure, you need:

- the [Tiled editor](https://www.mapeditor.org/) software
- "tiles" (i.e. images) to create your map (this starter kit provides a good default tileset for offices)
- a web-server to serve your map (this starter kit proposes to use Github static pages as a web-server which is both free and performant)

## Getting started

On the [Github repository page](https://github.com/thecodingmachine/workadventure-map-starter-kit),
click the **"Use this template"** button. You will be prompted to enter a repository name for your map.

![](docs/create_repo.png)

Be sure to keep the repository "Public".

In your newly created repository, click on the **Settings tab** and scroll down to the **GitHub Pages** section.
Then select the **gh-pages** branch. 

![](docs/github_pages.png)

Wait a few minutes a Github will deploy a new website with the content of the repository.
The address of the website is visible in the "GitHub Pages" section.

![](docs/website_address.png)

Click on the link. You should be redirected directly to WorkAdventure, on your map!

## Customizing your map

Your map is now up and online. You need to customize it.

### Cloning the map

Start by cloning the map. If you are used to Git and GitHub, simply clone the map
to your computer using your preferred tool and [jump to the next chapter](#loading-the-map-in-tiled).

If you are new to Git, cloning the map means downloading the map to your computer.
To do this, you will need Git, or a Git compatible tool. Our advice is to use
[GitHub Desktop](https://desktop.github.com/).

### Loading the map in Tiled

The sample map is in the file `map.json`.
You can load this file in [Tiled](https://www.mapeditor.org/).

Now, it's up to you to edit the map and write your own map.

Some resources regarding Tiled:

- [Tiled documentation](https://doc.mapeditor.org/en/stable/manual/introduction/)
- [Tiled video tutorials](https://www.gamefromscratch.com/post/2015/10/14/Tiled-Map-Editor-Tutorial-Series.aspx)

### About WorkAdventu.re maps

In order to design a map that will be readable by WorkAdventure, you will have to respect some constraints.

In particular, you will need to:

- set a start position for the players
- configure the "floor layer" (so that WorkAdventure can correctly display characters above the floor, but under the ceiling)
- eventually, you can place exits that link to other maps

All this is described in the [WorkAdventure documentation](https://github.com/thecodingmachine/workadventure/#designing-a-map).
Please be sure to check it out. 

### Pushing the map

When your changes are ready, you need to "commit" and "push" the changes back to GitHub.
Just wait a few minutes, and your map will be propagated automatically to the GitHub pages web-server.

TODO: describe how to push

## Attribution

### Tiles and tilesets

* base_out_atlas.png: CC-BY-SA 3.0 by LPC, https://lpc.opengameart.org/
* bird_2_robin.png: CC-BY-SA 4.0, "[LPC] Birds" by bluecarrot16, commissioned by castelonia. https://opengameart.org/content/lpc-birds
* bird_3_robin.png: CC-BY-SA 4.0, "[LPC] Birds" by bluecarrot16, commissioned by castelonia. https://opengameart.org/content/lpc-birds
* Bowlingtreff_Neubau.png: CC-BY-SA by Monika Hegenberg
* bsconf.png: CC0 by Chaos_99
* Bubbles.png: CC-BY-SA 4.0 by Spring
* butterfly.png: CC-BY-SA 4.0 by Jordan Irwin (AntumDeluge), https://opengameart.org/node/79095
* chaos_zone_shared.png: By Chaoszone, https://github.com/chaosz0ne/shared
* chestnut-002.png: CC-BY-SA 3.0 by Yar, https://opengameart.org/node/81685
* deer female calicumtrice.png: CC0 by Calciumtrice & Jordan Irwin (AntumDeluge)
* dezentrale_logo_96x64.png: dezentrale e.V., https://dezentrale.cloud
* fantasy.png: FREE RPG Tileset 32x32 by pipoya https://pipoya.itch.io/pipoya-rpg-tileset-32x32
* floors.png: by bluecarrot16, Lanea Zimmerman (Sharm), William Thompson (William.Thompsonj), Hyptosis, SpiderDave, Cougarmint, Stephen Challener (Redshrike), Bonsaiheldin, Tyler Olsen (Roots), Jetrel, jestan, The Open Surge team (http://opensnc.sourceforge.net), Gaurav Munjal, Reemax, Silveira Neto, bleutailfly, Casper Nilsson, NaRNeRZz, Buch, keith karnage, Arthur Carvalho, Guilherme Vieira (n2liquid), Chris Hamons (maintainer). CC-BY-SA 4.0.
* floortileset.png: CC-BY-SA by CERT (cert.ccc.de)
* foto_esszimmer: CC-BY-SA by Monika Hegenberg
* Fox_idle.png: CC0 by ScratchIO
* headgear-OCAL.png: CC0 by openclipart.org
* Insekten.png: CC0 by Uncle_Gart
* interior.png: CC-BY-SA 3.0 by LPC, https://lpc.opengameart.org/
* kulturlichter.png: CC-BY-SA by Andreas Bräu, blog.andi95.de
* lpc-doors-animated-1.png: CC-BY 3.0 by LPC, https://lpc.opengameart.org/, Original wood and dungeon doors by Lanea Zimmerman (AKA Sharm).
* lpc-doors-animated-2.png: CC-BY-SA 3.0 by LPC, https://lpc.opengameart.org/, Original castle door by Daniel Armstrong (AKA HughSpectrum)
* lpccatratdog.png: CC-BY-SA 3.0 by LPC, https://lpc.opengameart.org/  
* LPCsnowTrees.png: CC-BY-SA 3.0 by Sharm, https://lpc.opengameart.org/
* Makerspace.png: CC0 by Chaos_99
* mapUtilities.png: CC0 by CCCV, https://git.cccv.de/rlab/world-tiles
* mountain_landscape.png: Daniel Cook's 2d Circle Graphic Archive
* museumsmenschen.png: CC-BY-SA by Monika Hegenberg
* museumsmenschen_klein.png: CC-BY-SA by Monika Hegenberg
* nkm_tiles.png: CC-BY-SA by Andreas Bräu, Monika Hegenberg
* office_1.png: By Milkian, Enterbrain and Mack, https://www.deviantart.com/milkian
* otters.png: CC0 by Spring
* Panda.png: CC-BY-SA 3.0, @danielmahon
* pigeon-NESW.png: CC-BY 3.0 by Onno Timmerman (Enquest) & Jordan Irwin (AntumDeluge), https://opengameart.org/node/84675
* plant repack.png: CC-BY-SA 3.0 by LPC, https://lpc.opengameart.org
* poke.png: ChaoticCherryCake and others, see http://fav.me/d6321qy
* polar_bear.png: CC0, https://opengameart.org/content/bears
* reindeer-m-run.png: CC0 by Calciumtrice & Jordan Irwin (AntumDeluge)
* SF_Inside_B.png: by PandaMaru
* Shark1.png: OGA-BY 3.0 by Pillarist
* spider.png: CC-BY-SA 3.0 by Tuomo Untinen
* sprechblase.png: CC-BY-SA by Monika Hegenberg
* squirrels-1.png: CC0, Squirrels by Dennis Payne based on work by Luis Zuno @ansimuz and 494949
* Stern.png: CC-BY-SA by Andreas Bräu, Monika Hegenberg
* StreetSpriteBright.png: CC0 Made by XenonMax
* sultana.png: CC0 https://opengameart.org/node/12210
* terMeer.png: CC-BY-SA by Monika Hegenberg
* terMeer_gezeichnet.png: CC-BY-SA by Monika Hegenberg
* terrain.png: CC-BY-SA 3.0 by LPC, https://lpc.opengameart.org/
* terrain_atlas.png: CC-BY-SA 3.0 by LPC, https://lpc.opengameart.org/
* tileset_deviant_milkian_2.png: By Milkian, Enterbrain and Mack, https://www.deviantart.com/milkian
* tileset_deviant_milkian_3.png: By Milkian, Enterbrain and Mack, https://www.deviantart.com/milkian
* whale.png: CC0 by Mepavi @ You're Perfect Studio
* Zuege.png: CC-BY-SA 3.0 by Hansjörg Malthaner, http://opengameart.org/users/varkalandar

### Sounds

CC0 from [freesound.org](https://freesound.org)
CC0 from [OpenGameArt.org, Milkytracker](https://opengameart.org/content/my-street)

### Videos

### Fonts

#### Lato

Lato-Hairline.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.
Lato-HairlineItalic.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.
Lato-Light.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.
Lato-LightItalic.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.
Lato-Regular.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.
Lato-Italic.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.
Lato-Bold.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.
Lato-BoldItalic.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.
Lato-Black.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.
Lato-BlackItalic.ttf: Copyright (c) 2010-2011 by tyPoland Lukasz Dziedzic (team@latofonts.com) with Reserved Font Name "Lato". Licensed under the SIL Open Font License, Version 1.1.

#### Kalam

Kalam-Regular.ttf: Copyright (c) 2014 Indian Type Foundry (info@indiantypefoundry.com)
Kalam-Bold.ttf: Copyright (c) 2014 Indian Type Foundry (info@indiantypefoundry.com)
