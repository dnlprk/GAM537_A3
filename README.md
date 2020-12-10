# GAM537 - ASSIGNMENT 3

## Overview

The Player Character is a robot in an experimental facility that is malfunctioning. They have to get to the control panel to fix it.

## LEVEL 1

### Design
This level is the ground level and public face of the robot company. It’s where staff can hang out and where non-authorized personnel can come and see the facility. However, since things are going wrong and people have evacuated leaving things in a bit of a state.
The maze layout was designed to be simple, objects (desks, crates, etc.) are placed in areas so that the player can orient themselves. 
Walls are made of different material for the same reason. Blank areas are left for the future implementation of other checkpoints or alternative routes.

### Lighting
As an interior level, the sky dome and directional lighting were not required especially since the facility is supposed be experiencing a malfunction. No overhead lights are used, but the character being a robot has their own point light allowing the player to be able to see somewhat.

Flickering point lights as learned in the lab to create the impression of a malfunctioning facility as well as helping the player know where to go.
 
### Objects
As mentioned objects such as a work table, chairs and crates were used to help orient the player as well as to create the impression that people spend time there and that they left in a hurry.

The player is able to traverse to the next level by a box trigger placed near a door. Walls and lighting are the main feature of this level as the player must navigate though the maze without the ability to destroy anything in the environment.


Note on Future Iterations:
In the next iteration, the ability for the player to manipulate the environment may be added. Since the character is a robot they could patched into the environment and have the ability to open and close doors, move platforms etc., which could be used to create puzzles as well as a maze. This could be done using similar BluePrints to the ones used in Lab 2.



## LEVEL 2

### Design
This level is meant to be the secret area of the facility where the real work is taking place. For this reason, and to increase the level of difficulty only a single wall is made of different material and there are less objects to help the player orient themselves.
Unfortunately, although the goal of making it more difficult to navigate was achieved this also made this level more tedious and monotonous in terms of the visuals and gameplay. For the next assignment, this level should be made less maze-like by removing some walls and incorporating puzzle or platformer game mechanics.

### Lighting
The lighting is bright and less claustrophobic then Level 1, allowing the player to see better but also gives them less clues about where to go.
A Sky and Directional light are used along with point lights. Everything is made to look shiny, new and high-tech.
 
### Objects
This level contains several more pickups (10 total through the game). These are toolboxes, tools, etc., essentially things that someone might need to repair a malfunctioning control panel.

Like level 1 there are also decorative objects to help orient the player, although of this level there are considerably less to make navigation more difficult. At this stage in development there is no feedback to the player that some of the doors are false or red herrings and it isn’t clear which of the high-tech equipment is meant to be the control panel they need to find.
This can be fixed by having more messaging in the game in future iterations as well as incorporating the pickups into a score or health system.
