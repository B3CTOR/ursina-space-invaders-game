## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info

This is a simple endless game programmed in Python 3.9 with the free and open source engine Ursina. In the assets directory you will find the source files of the textures and the sounds so you can modify them.

You will take control of a spaceship and shoot your enemies. To move the spaceship press 'a' to move to the left and 'd' to move to the right, you can shoot by pressing 'space'.
At the beginning you will see your spaceship and the game title, shoot once to show the "menu" options and then, shoot to the Play square.

There are three types of enemy, the basic one, it will move towards you every time you shoot, it has 1HP and will give you 5 points. The second enemy will move towards you in a static velocity, it has 2HP and will give you 10HP. The last enemy is the hardest one, it will move as the previous enemy but slower, it has 4HP and will give you 50 points.

I have tried to convert the .py file with all the assets into a single .exe file but I couldn't, if you download the program and convert it into a one .exe file successfuly contact please contact me.

## Technologies

The following package was used in this game:

- Ursina
```
$ pip install ursina
```
https://www.ursinaengine.org/


This is the game engine used in this project.

Note: To use this package, you will need Python 3.6+

- Graphics

To make the pixel-art graphics I used the following website:

https://www.piskelapp.com/

- Sounds

To make the sounds I used the following software:

https://www.bfxr.net/

- Music and Game Over sound effect:

https://youtu.be/0NGMTT88p6M

https://youtu.be/br3OzOrARh4


## Setup

As I said I couldn't convert the game into a single .exe program, so the following way is the onle one to execute the game:
```
$ python space_invaders.py
```


