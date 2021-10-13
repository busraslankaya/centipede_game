# Centipede game with python


**Game Features**
- Each icon hit by the player has a point value. Scores are as follows;
- >Mushrooms and Poisonous Mushrooms: 1 point (four strokes required to destroy)
- >Centipede (Trunk): 10 points
- >Centipede (Head): 100 points
- >Flea: 200 points (Takes two hits. The first hit accelerates, the second hit destroys it)
- >Spider: 300, 600, 900 points (The closer the Point Spider is to the Insect Bug when hit)
- >Scorpio: 1,000 points When a mushroom patch is reset after a player has died, 5 bonus points 
restored to the player are partially destroyed / poisoned mushrooms.
-There are 3 lives in the game. When you touch poisonous mushrooms, spiders, fleas, scorpions or 
centipedes, one health is reduced. And when it's over, the game is over.
-When the centipede is completely hit, the game pass in difficult stages and the game continues until it 
is renewed.
-The main aim of the game is to achieve the highest score.

**There are 3 difficulty modes in the game. easy normal and hard mode.**

The game has pause function.When the user press “P” display screen will pause, the game continues 
from where it left off when the user press “C”.


The user can mute the game with “M” in menu,easy or hard mode and handbook display screens. 
The user also can unmute the game with “N” in menu,easy or hard mode and handbook display 
screens.


**Scores:**


The player gains 10 points when shots any piece of centipede. 

The player gains 50 points when shots spider.

The player gains 30 points when shots flea.

The player gains 3 points when shots mushroom.



**Main Class:**


-We added fonts.

-We define set up game map after that we draw game map for each level.

-We define handbook game mode and we defined speeds of instructions and quit key.

-We defined game mode menu: 

We set key down and up

We added options.

-We defined game mode game over:
The location of the options adjusted when the game ended . 
We set option’s keys when the game ended.

-We defined game mode easy level.We set fire key,centipede’s move,mushrooms,activated spider and 
we write collisions for each.We wrote score and the player lives on the display screen.

-We defined game mode normal level.We set fire key,centipede’s move,scorpion,mushrooms,activated 
spider and we write collisions for each.We wrote score and the player lives on the display screen.

-We defined game mode hard level.We set fire key,centipede’s move,scorpion,mushrooms,activated 
spider,flea and we write collisions for each.We wrote score and the player lives on the display screen.
