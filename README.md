# Caesar-Cipher-
Caesar Cipher in Python
To perform Caesar cipher encryption and decryption in Python, you can use the ord() and chr() functions to convert characters to their ASCII values and vice versa. Here’s a step-by-step guide and example code for both encryption and decryption:

Encryption
Define the shift value.
For each character in the text:
Convert the character to its ASCII value using ord().
Apply the shift to the ASCII value.
Convert the shifted ASCII value back to a character using chr().
Append the new character to the encrypted text.
Decryption
Define the shift value.
For each character in the encrypted text:
Convert the character to its ASCII value using ord().
Apply the reverse shift to the ASCII value.
Convert the shifted ASCII value back to a character using chr().
Append the new character to the decrypted text.
