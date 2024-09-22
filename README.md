# DES Encryption and Decryption using Python
This Python script demonstrates encryption and decryption of a message using the Data Encryption Standard (DES) in EAX mode. It utilizes the Crypto.Cipher module from the pycryptodome library and generates a random 8-byte secret key for encryption. The script includes two primary functions: encrypt() and decrypt().

## Features:
Encryption: Converts a user-provided message into ciphertext using DES in EAX mode, returning the nonce, ciphertext, and authentication tag.
Decryption: Recovers the original plaintext message from the provided ciphertext, nonce, and tag, verifying the authenticity of the message.
Error Handling: The decryption process verifies the integrity of the message using the tag. If verification fails, an error message is displayed.
## Usage:
The user inputs a message to be encrypted.
The encrypted message is displayed in ciphertext format.
The script attempts to decrypt the message and either displays the original message or an error if decryption fails.
## Installation:
pycryptodome library (pip install pycryptodome)

### Steps to Install

1. **Clone the repository**

   ```bash
   git clone https://github.com/sahilsingh0532/Text_Encrypter.git
2. **Install necessary libraries using pip command**
   ```bash
     pip install PyCryptodome
3. Use
