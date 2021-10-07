# -Sayollo-Home_Challenge
[Bar Perez]Home_Challenge

Gameplay:
First scene is only a start button, Second scene is the game where you control the fly force of a cat with 
clicking on your left mouse button (mouse0). You collect as much fruits as you can while avoiding the flying birds.
When player dies a menu shows up. The menu presents current score,highscore and 2 options to retry or go to back to the menu in the first scene.

Install:
Export the unity package and go to Build to update the scene order 0-StartMenu 1-Game

Game requirements:
Except requirment 4.Sounds.d.button_click all requirements as been met.

Code:
General stuff are controlled by Managers(GameManager,UiManager,AudioManager) using Singeltons.
Fruit and Enemy has behaivor engine that control what they do.
Background script to procedurally generate and move the background.
Player script to control movement,particle system activation and collisions triggers.
Animations.
There are code remarks in the scripts as well.
