# Hamming distance
Due to the characteristics of the communication line used to transmit messages from point A to point B, each bit of the received message with a probability of 0.001 contains an error.
From point A to point B, one of the n messages m1, m2, ..., mn was sent. At point B, the message s was taken.
Your task is to determine the most likely source message. Obviously, it will be one of those messages, the Hamming distance between which and the string s is minimal.
The Hamming distance of two rows a and b of the same length is the number of positions where these rows differ (the number of elements in the set {i | 1 ≤ i ≤ | a |, ai bi}).
The first line of the input file INPUT.TXT contains s - the received message. The second line contains an integer n - the number of messages that could be sent. The following n lines contain mi - these messages. The lengths of all messages are equal (| s | = | m1 | = | m2 | = ... = | mn |). Messages are non-empty, they consist only of characters 0 and 1. The size of the input file does not exceed 60 Kb.
In the first line of the output OUTPUT.TXT file, output k - the number of messages where the minimum Hamming distance is reached. In the second line print in ascending order of k numbers - the numbers of these messages.
