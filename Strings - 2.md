# Strings - 2
The set of strings is S = {s<sub>1</sub>, s<sub>2</sub>, s<sub>3</sub>, ..., s<sub>n</sub>}. It is necessary to find the number of string `s`<sub>`i`</sub> from `S`, representable as a concatenation of two strings `s`<sub>`j`</sub> and `s`<sub>`k`</sub> from `S` (s<sub>i</sub> = s<sub>j</sub>s<sub>k</sub>, `j` and `k` may coincide).

The input contains a set of strings `S` - one element per string. The i-th line of the input file contains `s`<sub>`i`</sub>. It denotes the end of the input data and is not included in `S`.

All `s`<sub>`i`</sub> consist only of small letters of the English alphabet and have a length of from 1 to 100 characters. There are no more than 240 strings in the input.

In the output the answer without leading zeros.

| INPUT                      | OUTPUT                 |
|----------------------------|------------------------|
| aa<br>aaaa<br>ab<br>abaa   | 2                      |
| abc<br>bcd<br>def          | 0                      |
