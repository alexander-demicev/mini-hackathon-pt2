# Line strength
Let the string s = s1s2 ... sn be given. We call its kth (k> 0) degree sk the string sk = s1s2. . .sns1s2. . .sn ...... s1s2 ... sn (k times). For example, the third degree of the abc string is the abcabcabc string.
The root k of a degree from the string s is the string t (if it exists) such that tk = s.
Your task is to write a program that finds the power of a string or the root of it.
The first line of the input file INPUT.TXT contains the string s, it contains only small letters of the English alphabet and has a nonzero length not exceeding 1000.
The second line of the input file contains an integer k ≠ 0, | k | <100001. If k> 0, then it is necessary to find the k-th power of the string s, if k <0, then it is necessary to find the root of power | k | from s.
In the output file OUTPUT.TXT output a line that is the answer to the problem. If the length of the answer exceeds 1023 characters, output only the first 1023 characters. If the required string does not exist, output NO SOLUTION.
