# BattleCity
Implementation *simple* BattleCity-like game
(please, see BattleCity (1985) game for a reference if you like - https://www.youtube.com/watch?v=MPsA5PtfdL0).

Game reference - https://strategywiki.org/wiki/Battle_City/How_to_play
Overview

Players control a tank and shoot projectiles to destroy enemy tanks around the playfield. The enemy tanks enter from the top of the screen and attempts to destroy the players base (represented on the screen as a phoenix symbol), as well as the player's tank itself. A level is completed when the player destroys 20 enemy tanks, but the game ends if the player's base is destroyed or the player loses all available lives. Note that the player can destroy the base as well, so the player can still lose even after all enemy tanks are destroyed.


Players Tank

Players control yellow and green tanks. Tank can only have one of its own shots on the screen at one time, and may not fire again until the shot hits an enemy or collides with a wall. The tank can be destroyed by one enemy bullet.

Controls:
  - Left/Right/Up/Down - move yellow tank
  - Space - fire yellow tank
  - A/D/W/S - move green tank
  - Tab - fire green tank

Enemy Tank

1. Basic Tank:
  - Health - 1
  - Movement Speed - 1 (slow)
  - Bullet Speed - 1 (slow)
  - Description - Generally poses little threat. Moves slower than players, fires at the same speed default powerю


Environment

There are a few different types of obstacles scattered around each stage. The key to surviving is knowing how to use them to your advantage.

1. Brick Wall:
  - Tanks and bullets cannot pass through this.
  - Can be destroyed by being shot four times (two times when offensive power is tier four/max) on the same side.
2. Optional: Steel Wall
  - Stops tanks and bullets completely.
  - Can only be destroyed if hit twice on the same side by maximum power level bullets (tier four).

