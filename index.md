---
layout: default
---
Crayola Crayons have been in production for over a century, but this isn't the case with all the colors you see. With hundreds of different colors, we have seen different Crayola crayons come in and out of production. With this, each crayon has a production age. Can you determine which Crayola crayon is oldest?

![GettyImages-1055965132-9989ff7a5fb94515b1d1982bdfc69b62](https://user-images.githubusercontent.com/113651118/236330121-66bfff0c-a050-485f-ac6c-544f9af26376.jpg)

## What's the BIG idea?
The goal of this project is to create a fun interactive game using crayon data we collected. We based our game off of a game where the number of google searches a phrase has are compared. We used Crayola Crayon data instead of google search data to bring a sense of nostalgia and add colors to our game. Using the crayon data also allowed us to continue utilizing our data from our previous project.

## Unique Features
Our game strives to bring back that sense of nostalgia that you associate with Crayola crayons. With over 150 individual colors and ages ranging from 1 all the way to 120 years old we hope to keep you engaged all the way till the end!

## How to Play
To run this game, clone the game repository from this repository [https://github.com/olincollege/crayola_higher_lower] to your python environment. Our game utilizes pygame as a key library for display and interaction which requires installation. We also use pandas to store the crayon data which also requires installation if not installed already. After running the installation for pygame and pandas in the terminal, you can run the game by running ```python crayon_full_game.py``` in the terminal.

Install with pip:
```
pip install pygame
pip install pandas
```
Graphics files are stored in the ```/assets``` folder and are called in ```crayon_view.py```

### Start Screen
Once you start the program you will be greeted by the following screen. 
This screen includes instructions on how to start and play the game.
![gameplay_start](https://user-images.githubusercontent.com/113651118/236334877-d947bcdb-9f9f-4deb-9886-002027139568.png)

### Gameplay Screens
Once you start playing the game, two crayons will appear with the corresponding name and color, for you to compare. The goal is to choose the crayon which has been in production longer. After you choose the actual age will appear and the score will update.
![gameplay_running](https://user-images.githubusercontent.com/113651118/236342612-0dcd1009-a83b-496b-98f8-aac897a13c59.png)

### Ending Screen
If you choose the wrong crayon the game will automatically end. The Screen will update to show your final score and provide you with instructions to either play again or quit the game.
![gameplay_end](https://user-images.githubusercontent.com/113651118/236343314-0146cb22-d829-492e-925e-46dbd1508abd.png)


### Video of Gameplay
[Gameplay Video](https://user-images.githubusercontent.com/113651118/236348136-7031897f-a365-466f-98b4-bc1d42c8eceb.mp4)


##About The creators
**Lily Dao** I took SoftDes to expand my breadth of knowledge and gain a better understanding of how the mechanical world connects with the software world. This class has allowed me to explore new areas and challenge myself in a field that I am generally unfamiliar.
**Chris Bocamazo** As a MechE, I wanted expand my limited scope of programming knowledge to a more frequently used and applicable language like Python.  I feel more equipped to implement code in any project going forward.
**Owen Johnston** I took SoftDes because I feel as the world becomes more technology dependent, software design is an important skill to have. This class has opened my eyes to new ways of creating and viewing the world around us.

