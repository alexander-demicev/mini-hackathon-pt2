# Numerologist
## Complexity 24%

To predict the fate of a person, a numerologist takes a person’s life time in seconds, then adds all the digits of that number. If the resulting number consists of more than one digit, the operation is repeated until the number remains one digit. Then, according to the resulting figure and the number of operations required to convert the number into a single digit, the numerologist predicts the fate of the person. A numerologist doesn’t know how to count, and the numbers he works with can be very large. Write a program that would do all the calculations for him.
The input contains the number N - the lifetime of a person in seconds (1 ≤ N ≤ 101000).

The output contains two numbers separated by a space: the resulting digit from the number N and the number of conversions.

| INPUT  | OUTPUT|
|--------|-------|
| 1      | 1 0   |
| 10	 | 1 1   |
| 99	 | 9 2   |
