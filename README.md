# Custom Multi-layer Encryption-Decryption System :-

Welcome to a Python-based custom encryption-decryption system that layers multiple techniques to secure your text! 
This project simulates real-world encryption pipelines, built completely from scratch (with zero built-in crypto libraries).

## Features :-
✤ **Caesar Cipher** — classic shift-based encryption
✤ **String Reversal** — to distort patterns and enhance obfuscation
✤ **ASCII Shifting** — adds extra byte-level transformation
✤ Supports **file input & output**
✤ Interactive **command-line interface**

## How It Works :-

###  Encryption Pipeline :
1. **Caesar Cipher** → Shifts letters using a key
2. **Reverse String** → Reverses the entire message
3. **ASCII Shift** → Increases each character's ASCII value by 1

###  Decryption Pipeline :
1. **ASCII Unshift** → Decreases ASCII value by 1
2. **Reverse String**
3. **Caesar Decrypt** → Reverses the Caesar shift

## 📂 Project Structure :-
CustomEncryptionSystem/
├── Main.py # The main encryption/decryption script
├── Input.txt # Input text samples (one per line)
├── Output.txt # Output (encrypted/decrypted) text
└── README.md # This file 

## Usage :-

Run the program via terminal or any **Python IDE** like **PyCharm**.
