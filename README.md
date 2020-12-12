# GAM537 - ASSIGNMENT 3

## Overview

The Player Character is a robot in an experimental facility that is malfunctioning. They have to get to the control panel to fix it.

The idea is their consciousness is built into the facility and so they are able to assume the role of one of the robots. Perhaps they were a helper computer that has to take over when humans have messed things up, or maybe they are a scientist who has “gone too far” as they so often do in sci-fi.
Maybe they were the ones who broke things in the first place!


## LEVEL 0
When the game opens, the player is lost and doesn’t know where or who they are. It’s a small level as confusion can get tiresome fast, and when they head toward the light in the next level they are reborn – as a fantastic cyborg creature.


## LEVEL 1

### Design
This level is the ground level and public face of the robot company. It’s where staff can hang out and where non-authorized personnel can come and see the facility. However, since things are going wrong and people have evacuated leaving things in a bit of a state.
The maze layout was designed to be simple, objects (desks, crates, etc.) are placed in areas so that the player can orient themselves. 
Walls are made of different material for the same reason. Blank areas are left for the future implementation of other checkpoints or alternative routes.


## LEVEL 2

### Design
This level is meant to be the secret area of the facility where the real work is taking place. For this reason, and to increase the level of difficulty only a single wall is made of different material and there are less objects to help the player orient themselves.
Unfortunately, although the goal of making it more difficult to navigate was achieved this also made this level more tedious and monotonous in terms of the visuals and gameplay. 

### Objects
This level contains several more pickups (10 total through the game). These are toolboxes, tools, etc., essentially things that someone might need to repair a malfunctioning control panel.


## LEVEL 3

### Design

The final level is a rooftop garden… or it should be, but the facility is malfunctioning so the environment is running amok. 
Like the other levels, it is a maze however it is larger with more room to maneuver to allow room for the NPCs (including enemies). The foliage from Assignment 2 also serves as a cue to solve the maze, since there are other challenges introduced in this level, is not intended to be overly hard.


## PLAYER CHARACTER

The Player Character has several animations including walk forward, left, right, crouch, jump and sprint/flight. They also have a fully functioning collider which means they cannot take shortcuts in the maze and are stopped by the glass wall.
The white and gold design went especially well as that was the main color scheme, particularly for the last two levels.

### Controls
The standard WASD key commands are used for basic directional movement and the spacebar is use for jumping.  The player is now also able to fight, save their point in the game and respawn their saved position. 


## OTHER CHARACTERS

### NPCs
On level 2, the character meets two human characters. Although they eagerly follow the player along,
they don’t really seem to be much help…

### Enemies
A mysterious wraith chases the player in Level 1, lumbering robots appear in level 2 and 3 patrolling the area. In Level 3, some of these enemies attack the character when they see her.


## RESPAWN/SAVE SYSTEM

When the players hits the O key, their position in the game is saved as indicated on screen. When they hit the R key they are returned to their saved location (aka the game loads).

This was an attempt to make rapid use of the save/load function in-game, especially since they are so many chasing enemies the player could use this function to escape. However, it can be a bit disorienting on levels where there are less visual cues.


## MELEES

Some of the baddies are equipped to deal with our character, but as a high-tech robot she packs quite a punch herself. Along with patrolling and attacking, these enemies also have a death animation. If the player punches them right they fall over and disappear after a few seconds.

## LINKS

See gameplay @ https://youtu.be/F7ng0uq7bTQ



