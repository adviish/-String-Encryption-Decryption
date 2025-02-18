# -String-Encryption-Decryption
This repository contains the documentation of two classic encryption methods: Caesar cipher and Vigenère cipher.

Caesar Cipher
The Caesar cipher is a simple substitution method where each letter is replaced with another letter shifted by a fixed number of positions in the alphabet.

Encryption
A key (shift value) is chosen – an integer.
Each letter of the input text is shifted forward by the given number of positions.
If the shift exceeds the alphabet boundary, it wraps around to the beginning.

Decryption
The same key (shift value) is used.
Each letter of the encrypted text is shifted back by the specified number of positions.

Vigenère Cipher
The Vigenère cipher is a more complex substitution method that uses a keyword to encrypt text multiple times.

 Encryption
A keyword is chosen.
Each letter of the text is shifted by a value corresponding to a letter in the keyword.
The keyword repeats along the length of the text.

Decryption
The same keyword is used.
Letters of the encrypted text are shifted backward based on the keyword values.
