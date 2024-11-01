# 08 Caesar Cipher

This project is a simple encryption and decryption program using the Caesar cipher. It was created as the **Day 08 Challenge** from Dr. Angela Yu's Python Pro Bootcamp to practice Python fundamentals, including functions with parameters, loops, and user input handling. 

## Table of Contents
- [Overview](#overview)
- [How It Works](#how-it-works)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Example](#example)
- [Acknowledgements](#acknowledgements)

## Overview
The Caesar cipher is a basic encryption technique where each letter in a text is shifted by a specific number of positions in the alphabet. This project allows users to both encrypt and decrypt messages by choosing a shift amount and direction (`encode` or `decode`).

## How It Works
The program consists of the following key components:
- A function `caesar()` to handle both encryption and decryption based on the user’s choice.
- A loop allowing users to re-run the program until they decide to exit.

## Features
- **Encrypt messages** by shifting letters forward in the alphabet.
- **Decrypt messages** by shifting letters backward to the original text.
- **Preserve special characters and spaces** in the message (only alphabetic characters are shifted).
- **Loop function** for continuous encoding and decoding until the user decides to quit.

## Getting Started
1. Clone this repository.
2. Ensure you have Python 3 installed.
3. Run the script from the command line.

```bash
python caesar_cipher.py
```

## Usage
1. Enter `encode` to encrypt a message or `decode` to decrypt one.
2. Provide the message text and shift number.
3. View the output text.
4. Choose whether to continue or exit.

## Example

### Encrypting
```plaintext
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello
Type the shift number:
1
Here is the encoded result: ifmmp
```

### Decrypting
```plaintext
Type 'encode' to encrypt, type 'decode' to decrypt:
decode
Type your message:
ifmmp
Type the shift number:
1
Here is the decoded result: hello
```

---
<section align="center">
  <code>coderBri © 2024</code>
</section>
