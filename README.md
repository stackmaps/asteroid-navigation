# asteroid-navigation

Intermediate project to learn about navigation algorithms using Python 3 and pygame.

In this project, you will create algorithms to navigate your spaceship through an asteroid field. To do this, you will need to learn about different pathfinding and collision detection techniques.

## Difficulty Level:  INTERMEDIATE

You should be fairly comfortable with Python, understanding topics such as control structures, loops, mathematics, and other basic programming concepts.

## The Story

Recently you have been given tickets to a Frankie Boyle comedy concert, HOWEVER, the special is to be given on the moon. And Saturn as well. You made the trip safely enough and enjoyed Frankie Boyle’s high-class comedy for 1 full hour, but the imbecillic politicians outlawed immigration from Saturn two full minutes ago. It’s really your fault for going there knowing your return trip would be compromised, but c'est la vie.  You observed a suspicious looking used rocketship that the Saturnians pulled out of a shed, and decided to steal it. Unfortunately there are a number of problems with the rocketship: it has a leaky oxygen supply, broken solar panels, and a ruined autopilot system. The technician who pulled it out said that your chances of survival were exactly 1 in 9,647,856,774,432,553. You, however, believe in your skills as a programmer, and decide to program your rocketship to arrive safely on Earth before your oxygen supplies run out. Your rocketship contains all the necessary boosters and lift-off capabilities, but the computer only has a Python interpreter for some reason best known to the folk of Saturn, with pygame installed for entertainment purposes.

## What you will learn

In this project, you will learn MORE about:
* Pathfinding
* Spatial Reasoning
* Graphics

## Setup

Make sure python is installed on your computer. For this project, you will need to install pygame, which can be done with `pip3 install pygame`

## Getting Started

Take a look at the attached python code in `navigation.py`. Try running it, and see what happens (you can do this by navigating to this directory in your terminal and typing `python3 navigation.py`). You should see your rocket, your goal, and the field of asteroids you will need to navigate to.

In the file `navigation.py`, you will see many empty methods. In order to successfully navigate the asteroid field without crashing, you will probably want to know if you are about to collide with an asteroid on any side of your ship. To figure this out, fill in four methods, topCollision, bottomCollision, rightCollision, leftCollision. To help you along, we have included a number of helpful variables, such as your ship’ s position (rocketX, rocketY), your ship’s size (rocketWidth, rocketHeight), and the positions of all the asteroids in the field in a list. We also have included the destination you want to reach, goalX and goalY. Start out by trying to implement those methods, and see if you can do it. You can start by printing out the results as your program runs to test them.

If you are having a hard time figuring out how you might go about this, you could look at our program to see how we detect collisions between the rocket and the asteroids.

## Writing the algorithm

Now that you have those methods, try creating a program to use those four methods to move towards the goal. A good start would be to make sure your program simply never crashes into an asteroid using those methods.

You get a score on the end based on the time your rocket took to reach the end, so try to optimzize your algorithm so it reaches the goal more quickly.

For a more complex and efficient solution, try researching the A* pathfinding algorithm (https://en.wikipedia.org/wiki/A*_search_algorithm) which could be a good method to solve this problem.

## License

Licensed under the Apache License: http://www.apache.org/licenses/LICENSE-2.0
