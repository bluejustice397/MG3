# MG3
## Devlog

### MG3 Devlog

1. The values for int and float are zero, the value for string is empty, and the value of bool is false.


2. The update method isn't called by the developer. Once you create it, the method is automatically called by unity every frame.


3. KickWeapon first uses the _lifeTimer variable to access the BeginTimer method using .Timer use timer components, specifically to set the duration time for the kick by passing _lifetimeSeconds into BeginTimer. Then in the Update method _lifeTimer accesses the IsFinished method to check if the timer has run out, in which case the kick is deactivated.


## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)