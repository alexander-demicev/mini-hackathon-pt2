# Game theory
One of the interesting objects studied in game theory is the so-called antagonistic games of two persons. Such games are characterized by a set of X strategies of the first player, a set of Y strategies of the second player, and a gain function K (x, y) (x from X, y from Y). If the sets of strategies X and Y are finite, then such a game is usually called matrix, since the payoff function K in this case is conveniently defined by a matrix.
Consider a matrix game in which X = {1, ..., n}, Y = {1, ..., m}. The matrix of winnings is denoted by K. The lower value of the game is the number maxi = 1..nminj = 1..m Kij. The upper value of the game is the number minj = 1..mmaxi = 1..n Kij. Note also that games in which the lower and upper values coincide are called games with a saddle point.
Given the matrix wins K for a matrix game. Find its upper and lower value.
The first line of the input file INPUT.TXT contains integers n and m (1 ≤ n, m ≤ 100). Then follow n lines of m numbers each. The j-th number of the i-th row is equal to Kij. All Kij moduli do not exceed 1000.
In the output file OUTPUT.TXT output the lower and upper value of the game through a space.
