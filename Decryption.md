# Decryption
Lets take a look on how simplest cipher works. Encrypted message consists of English letters, written in lower case and a space character. Encryption happens character by character. Each letter is assigned a number: a - 1, b - 2, ..., z - 26, '' - 27. Next, the character index is added to the number in the message modulo 27, and the result of the addition is presented in the number system with base 27 (0 , 1, ..., Q in upper case).
You must write a descrambler.

INPUT contains an encoded string, from 1 to 255 characters in length. The string is uppercase.

OUTPUT need to display the decryption of a given string, while the characters of the English alphabet should be displayed in lowercase.

| INPUT                             | OUTPUT                 |
|-----------------------------------|------------------------|
| L7MO	  						    | test                   |
|-----------------------------------|------------------------|
| 576J9FLF	  					    | decoding               |
