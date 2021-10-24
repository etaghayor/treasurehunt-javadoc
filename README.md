# treasurehunt-javadoc
The javadoc for our project called treasurehunt. Due to a github issue for importing large projects, feel free to view the whole project in the following link:
https://gitlab.com/taghayor/treasure-hunt
# 💎 Treasure Hunt
---
>_Will you collect all the treasures hidden in the depth of this land and be the king of all your rivals? Or will you fall into the abyss of nothingness and lose all you have gathered? This is your realm, all you have to decide is what to do with the time that is given to you.<br> 
-The Wizard_
---

## Introduction
Treasure Hunt is a multiplayer server-based game with a top-down view graphics implemented entirely in Java.

## Running the program

Make sure you have ```make``` installed on your machine. For Gradle to work, you have to set the java language level on your machine less than java 14.

Then to run the server simply use

```$ make server```

in treasurehunt directory.

after the server got started use

```$ make gui```

in treasurehunt directory to have a graphic interface for client. you can also use

```$ make client```

to play in textual mode
* to find the manual of commands to use : go to extended_subject.pdf <br>


## Play the game

Once you launched the gui, you have to choose a name and a character.
<br></br>
![screenshot](https://gitlab.com/taghayor/treasure-hunt/-/raw/master/src/main/resources/images/environment/envi_character_2.png "Choose your character")
<br></br>
Then, create your map :
you can vary the size of the map, the number of holes and treasures, and select a game mode, you have the 3 choices for game modes :
- Speeding contest : a time trial, the fastest wins
- Round by round : during this mode, you have to wait your turn to play
- For of war : the rules are a little bit different, you have a limited visibility around the player, you can't see the whole board.
<br></br>
  
![screenshot](https://gitlab.com/taghayor/treasure-hunt/-/raw/master/src/main/resources/images/environment/create_game_1.png "Can you open all the treasures?")

Once all the players are ready : the game starts; you can move with z, q, s, d. You have to recover the treasures, go around trees and dodge the holes.
<br></br>

![screenshot](https://gitlab.com/taghayor/treasure-hunt/-/raw/master/src/main/resources/images/environment/in_game_round_1.png "Can you open all the treasures?")

The game view for each game mode is unique, here is an image of the warfog mode:
<br></br>

![screenshot](https://gitlab.com/taghayor/treasure-hunt/-/raw/master/src/main/resources/images/environment/in_game_warfog_3.png "Can you open all the treasures?")


## Authors

- Chemseddine Benaziza
- Ellenor Taghayor
- Maël Chemeque
- Nouredine Lamamra
- Nolan Bled

## Credits

All assets right are resevered for:
- Dungeon tile set by [ansimuz](https://ansimuz.itch.io/patreons-top-down-collection?download)
- Characters collection by [Superdark](https://superdark.itch.io/enchanted-forest-characters)
- Main font called Pixeboy by [farhanramadhika](https://www.instagram.com/abascreative/)
 
## Contributions

Pull requests are welcomed. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Details
For more explanation about the project, please check this file:

[Report](Rapport Projet de programmation Treasure Hunt.pdf)

You can find a wide view of the whole project in our javadoc files:

[Project javadoc](https://etaghayor.github.io/treasurehunt-javadoc)
