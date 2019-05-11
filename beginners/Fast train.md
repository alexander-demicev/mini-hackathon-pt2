# Fast train

## Complexity 30%

Between the two cities A and B goes a train. For each train, it is known its departure time from A and the time of arrival in B.

Find the fastest train and its speed in the assumption that the length of the railway between A and B is 650 km.

INPUT contains an integer n (1 ≤ n ≤ 100). Each of the next n lines describes exactly one train.
A train description consists of its name, departure time and arrival time. The name of the train is a string from 1 to 50 characters long, enclosed in quotes. It can contain English letters, spaces, numbers, dashes (“-”) and underscores (“_”). Departure and arrival times are given in HH: MM format. Lowercase and uppercase letters in train names are different.
Travel time for each of the trains is at least one minute and does not exceed 24 hours.
It is guaranteed that the fastest train is determined uniquely.

OUTPUT output the name of the fastest train and its speed. Output the speed in kilometers per hour and round to the nearest integer by mathematical rules. Follow the output format given in the examples.


INPUT

3
"ER-200" 06:43 10:40
"Red Arrow" 23:55 07:55
"Express" 23:59 08:00

OUTPUT

The fastest train is "ER-200".
Its speed is 165 km/h, approximately.

INPUT

3
"Train1" 00:00 00:00
"Train2" 00:00 00:01
"Train3" 00:01 00:01

OUTPUT
The fastest train is "Train2".
Its speed is 39000 km/h, approximately.
