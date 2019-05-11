# Decryption
Consider the work of the simplest cipher. Encrypted message consists of English letters, written in lower case and a space character. Encryption happens character by character. Each letter is assigned a number: a - 1, b - 2, ..., z - 26, '' - 27. Next, the character index is added to the number in the message modulo 27, and the result of the addition is presented in the number system with base 27 (0 , 1, ..., Q in upper case).
You must write a descrambler.
The only line in the input file INPUT.TXT contains an encoded string, from 1 to 255 characters in length. The string is uppercase.
In a single line of the output file OUTPUT.TXT need to display the decryption of a given string, while the characters of the English alphabet should be displayed in lowercase.
