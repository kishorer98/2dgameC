# so long
so_long is a small 2D game using the MinilibX graphics library.

### How to compile?
Using the Makefile you can create the executable file *so_long* or *so_long_bonus*
```
make
```
or
```
make bonus
```

### Map
To run the program, it is necessary to choose one of the maps. Example:
```
make
```
or
```
./so_long_bonus assets/maps_bonus/big.ber
```
The map must be in *.ber* format and be composed of the characters below:
| Character | Description |
| --------- | ----------------------------------------------|
| 0 | free space |
| 1 | wall |
| P | player's starting position |
| And | exit |
| C | collectable |
| K (bonus) | enemy |

Below is an image of one of the maps:
![](./assets/images/screenshot.png)

### Gameplay
Basically, the player needs to collect all the stars around the map, avoiding enemies (bonus) and leaving at the end.
The amount of moves is shown on the terminal (or on the game screen itself, in the case of the bonus).

You can see the game running here: https://www.youtube.com/watch?v=IcEGdGYS2Tk

The images used are from the Terraria game.


#### More about School 42 you can find here: https://en.wikipedia.org/wiki/42_(school)