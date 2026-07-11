# 🔐 Basic Encryption & Decryption System (Caesar Cipher)

A simple Python-based encryption and decryption tool that implements the **Caesar Cipher** algorithm. This project allows users to encrypt and decrypt text messages using a customizable shift key while preserving uppercase letters, lowercase letters, spaces, and special characters.

---

## 📌 Project Overview

This project demonstrates the fundamentals of classical cryptography by implementing the Caesar Cipher algorithm in Python. It provides a simple command-line interface where users can:

- Encrypt plaintext messages
- Decrypt encrypted messages
- Choose their own shift key
- Perform multiple encryption/decryption operations in one session

This project was completed as part of my **DecodeLabs Cybersecurity Internship** to strengthen my understanding of basic encryption techniques and Python programming.

---

## 🚀 Features

- 🔒 Encrypt text using the Caesar Cipher algorithm
- 🔓 Decrypt encrypted text back to its original form
- 🔑 User-defined shift key
- 🔁 Continuous execution until the user exits
- 📝 Preserves:
  - Uppercase letters
  - Lowercase letters
  - Spaces
  - Numbers
  - Special characters

---

## 🛠️ Technologies Used

- Python 3
- Command Line Interface (CLI)

---

## 📂 Project Structure

```
Basic-Encryption-Decryption-System/
│
├── encryption.py
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/Basic-Encryption-Decryption-System.git
```

2. Navigate to the project folder

```bash
cd Basic-Encryption-Decryption-System
```

3. Run the program

```bash
python encryption.py
```

---

## 💻 Sample Output

```
---------------------------------------------
---------------------------------------------
   TEXT ENCRYPTION AND DECRYPTION SYSTEM
---------------------------------------------
---------------------------------------------

Enter the text to Encrypt :
Hello World

Enter the shift key:
3

The Encrypted message is:
Khoor Zruog

The Decrypted message is:
Hello World
```

---

## 📖 How Caesar Cipher Works

The Caesar Cipher is one of the oldest encryption techniques. Each letter in the message is shifted by a fixed number of positions in the alphabet.

Example:

```
Plain Text : HELLO
Shift Key : 3

Encrypted : KHOOR
```

During decryption, the shift is applied in the opposite direction to recover the original message.

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Fundamentals of classical cryptography
- Caesar Cipher encryption technique
- Python string manipulation
- ASCII value operations using `ord()` and `chr()`
- Conditional statements and loops
- Building interactive command-line applications

---

## 🔮 Future Improvements

- GUI version using Tkinter
- File encryption support
- Multiple encryption algorithms
- Brute-force attack demonstration
- Random key generation
- Save encrypted messages to a file

---

## 👨‍💻 Author

**Muhammad Hanzala Ejaz**

Cybersecurity Student | Python Developer | Aspiring Security Analyst

---

## 📜 License

This project is created for educational purposes as part of the **DecodeLabs Cybersecurity Internship**.
