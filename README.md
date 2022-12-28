# Alien Invasion

## How to start

1. Make sure you have installed python (recommended version: 3.6).
2. Install pygame: `pip install pygame`
    - Note: if your python version causes `metadata-generation-failed` error, try to install pygame with `pip install pygame --pre`
3. Start the game (*clone the repo and enter the dir*): 
```bash
python alien_invasion.py
```

## How to play

* **Arrow left/right**
> ship left/right

* **Space bar**
> shoot

* **Q**
> quit

## Description

In Alien Invasion, the player controls a rocket ship that appears at the bottom center of the screen.
The player can move the ship right and left using the arrow keys and shoot bullets using the spacebar.
When the game begins, a fleet of aliens fills the sky and moves across and down the screen. The player
shoots and destroys the aliens. If the player shoots all the aliens, a new fleet appears that moves
faster than the previous fleet. If any alien hits the player's ship or reaches the bottom of the screen,
the player loses a ship. If the player loses three ships, the game ends. 

## Contributing

...