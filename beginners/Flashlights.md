# Flashlights

## Complexity 30%

Alex wants to find out if one light bulb is better than 2, and decided to assemble a flashlight with two light bulbs. Now he wants to know how much a flashlight with two bulbs is better than a flashlight with one. Note that the light bulbs in the lantern with two bulbs are different from the light bulbs in the lantern with one light bulb. To do this, Alex shone a flashlight on the wall, and each of the bulbs lit a circle on it.

The efficiency of the flashlight Alex wants to evaluate through the area of the illuminated part of the wall. Alex guessed to measure the coordinates of the centers of the illuminated circles and their radii (which turned out to be the same). Moreover, the area illuminated by a flashlight with one light bulb is known, since described in the documentation attached to the flashlight. But what to do next, he does not know. Write a program that will help Mischa.

INPUT contain the coordinates (x1, y1) and (x2, y2) - the centers of the circles from the lamps of the flashlight Alex assembled. The third line contains the radius r of the circles described above, and the fourth line contains the area of illumination s with a flashlight from one bulb. All numbers are integers and satisfy the following constraints: 1 ≤ x1, y1, x2, y2, r ≤ 100, 1 ≤ s ≤ 105. Also note that the areas illuminated by different lanterns differ from each other by more than 10-3.

OUTPUT output "YES", if Alex's the flashlight is better than the old one (ie it covers a large area) and "NO" otherwise.
