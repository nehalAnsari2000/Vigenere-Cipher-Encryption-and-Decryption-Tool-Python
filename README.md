# Vigenère Cipher Encryption and Decryption Tool

This project is part of the **Scientific Computing with Python** certification from freeCodeCamp, where I learned essential programming concepts, including string manipulation. It is a Python implementation of the Vigenère cipher, a classic encryption method that uses a keyword to encrypt and decrypt text. This tool provides a simple and interactive way to encode and decode messages using a custom key.

## Features
- **Encryption**: Encrypt plaintext into ciphertext using a custom keyword.
- **Decryption**: Decrypt ciphertext back into plaintext using the same keyword.
- **Custom Key Support**: Use any keyword of your choice for encryption and decryption.
- **Non-Alphabetic Character Handling**: Preserves non-alphabetic characters (e.g., spaces, punctuation) during encryption and decryption.
- **Case Insensitivity**: Converts all text to lowercase for consistent processing.

## How It Works
The Vigenère cipher works by shifting each letter in the plaintext by a corresponding letter in the keyword. The shift is determined by the position of the keyword letter in the alphabet (A=0, B=1, ..., Z=25). This process is reversed for decryption.

### Example:
```
Plaintext:  hello
Keyword:    key
Encrypted:  rijvs
Decrypted:  hello
```

## Code Overview
The project consists of the following functions:

### `vigenere(message, key, direction)`
The core function that handles both encryption and decryption.
- **message**: The text to be encrypted or decrypted.
- **key**: The keyword used for shifting letters.
- **direction**: `1` for encryption, `-1` for decryption.

### `encrypt(message, key)`
Encrypts the plaintext using the provided key.

### `decrypt(message, key)`
Decrypts the ciphertext using the provided key.

This tool is a great way to learn about classical encryption techniques while practicing Python programming!

