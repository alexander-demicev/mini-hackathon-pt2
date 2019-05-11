# Check for cute
Consider a table containing n rows and m columns, each cell of which contains zero or one. We call such a table pretty if there is not a single 2 by 2 square filled with zeros or whole ones.
So, for example, table 4 on 4, located on the left, is pretty, and located on the right, table 3 on 3 is not.
Several tables are specified. It is necessary for each of them to find out whether she is pretty.
The first line of the input file INPUT.TXT contains the number t (1 ≤ t ≤ 10) of the input data. The following are descriptions of these sets. The description of each set consists of a line containing the numbers n and m (1 ≤ n, m ≤ 100), and n lines, each of which contains m numbers separated by spaces. The j-th number in the i + 1st line of the description of the input data is the element aij of the corresponding table. It is guaranteed that all aij are either zero or one.
For each set of input data, output in the OUTPUT.TXT file a single line containing the word “YES” if the corresponding table is pretty and the word “NO” otherwise.
