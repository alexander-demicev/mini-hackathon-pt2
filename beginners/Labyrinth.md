# Labyrinth
## Complexity 47%


Opening his eyes, Prince of Persia discovered that he was at the top level of the underground labyrinth of Jaffar. The labyrinth consists of `h` levels located strictly under each other. Each level is a rectangular area, divided into `m` x `n` areas. In some areas there are columns supporting the ceiling; the Prince cannot enter such areas.

A prince can move from one area to another adjacent free area of the same level, he can also break through the floor below and be a level lower (the floor cannot be broken through at the lowest level). Any movement takes the Prince 5 seconds.

At one of the sections of the lower level of the Prince is waiting for the Princess. Help the Prince find the Princess by spending as little time as possible.

The first line of the input contains the natural numbers `h`, `m` and `n`- the height and horizontal dimensions of the maze `(2 ≤ h, m, n ≤ 50)`. Further in the input file there are `h` blocks describing the levels of the maze in order from top to bottom. Each block contains `m` lines, `n` characters each: “.” Denotes a free area, “o” denotes a section with a column, “1” denotes a free area in which the Prince finds himself at the beginning of his journey, “2” indicates a free area, on which the princess lies. The characters "1" and "2" are found in the input file exactly once: the character "1" is in the description of the highest level, and the character "2" is in the description of the lowest level. Neighboring blocks are separated by a single empty line.

In the output the minimum time in seconds it takes the Prince to find the Princess. Since good always triumphs over Evil, it is guaranteed that the Prince can do it.


| INPUT                                                                            | OUTPUT                  |
|----------------------------------------------------------------------------------|-------------------------|
| 3 3 3<br>1..<br>oo.<br>...<br><br>ooo<br>..o<br>.oo<br><br><br>ooo<br>o..<br>o.2 | 60                      |

