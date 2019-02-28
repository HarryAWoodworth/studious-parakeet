# studious-parakeet
iOS Game created using spritekit. All sprite work was done by me using Piskel, a free online sprite creator. The ship is moved by tapping on the screen where you want the ship to move. The ship is in a constant 2 frame animation loop, and the stars are ceated using a thread that creates stars of random size and speed that move down the screen. The red meteors are created the same way, and the time between the meteors spawning decreases as the the player's score increases. When the player and a meteor collide, the player's score is reset to 0 and the time between meteor spawn is set back to the default value. The high score is saved in shared preferences, so will persist and will not be reset when opening the game.

Gameplay video: https://www.youtube.com/watch?v=XguP0WfsAGQ
