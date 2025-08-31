--- **flappy-bird-python** ---

**A simple Flappy Bird clone made in Python using pygame.**

*Features :*

classic flappy bird gameplay
gravity-based bird movement and jump mechanics
randomly spawning pipes with a fixed gap
score system increments as you pass pipes
game over on collision with pipes or screen edges
graphics use colored rectangles, no real decals.

*Installation*

Install Python 3.x
Install pygame:

pip install pygame

Clone this repository:
git clone <https://github.com/h4llowOs/Flappy-Bird-in-Python.git>

*Usage*

Run the game using:

python flappy_bird.py

*Notes :*

currently uses rectangles for graphics (replace with images for more polish)
no sound effects yet (could add jump/score/game over sounds)
could add high score saving and multiple levels
code is structured for readability and ease of modification

*Known bugs :*

score may increment incorrectly if the bird moves exactly through the center of two pipes simultaneously
bird can occasionally clip through the top of a pipe if jump velocity is very high
game over detection is immediate with no animation or delay
pipes sometimes spawn overlapping edges if the random height is at extreme values
no pause function (yet)
