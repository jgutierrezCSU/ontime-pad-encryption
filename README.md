# ontime-pad-encryption

How the program works in Sagemath:
1. Encodes a string S of text into binary. such as the input âHi!â = â010010000110100100100001â.

2. Generates k random bits using os.urandom, where k is the length of the binary string from previous part. 

3. Encrypt the binary string from part 1 with a one-time-pad, using the random bits from part 2 as the key,
 Prints the plaintext, the key, and the ciphertext.
