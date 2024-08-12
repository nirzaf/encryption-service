# Text Encryption/Decryption Web App

This is a simple client-side web application that allows you to encrypt and decrypt text using a custom encryption algorithm directly in your web browser. 

## Features

- **Encryption:** Encrypts the text you provide using a combination of bitwise operations (circular shift, multiplication, XOR).
- **Decryption:** Decrypts text that was encrypted using the same algorithm.
- **Copy to Clipboard:** Easily copy the encrypted or decrypted output to the clipboard.
- **Sleek Design:** Features a modern and clean user interface for a user-friendly experience.

## Algorithm

The encryption algorithm used in this app is a custom implementation that involves the following steps:

1. **Circular Shift:** The bytes of the input text are shifted left by a specific factor.
2. **Multiplication:** The shifted bytes are then multiplied by a constant factor.
3. **XOR Operation:**  An XOR operation is applied to the result using a secret key.
4. **Base64 Encoding:** The final encrypted bytes are encoded in Base64 for easy handling and display.

Decryption reverses these steps using the inverse operations and the same secret key.

**Note:** While this algorithm provides a basic level of encryption, it is **not intended for highly sensitive data**. For stronger security, consider using established encryption libraries.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/nirzaf/encryption-service.git 
