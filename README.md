# Quantum-Key-Distribution-and-Encrypted-Messaging-System
# 🔐 Steganographic Quantum Key Distribution & Encrypted Messaging System

> Final year project blending **Quantum Cryptography**, **Steganography**, and **AES Encryption** for post-quantum secure communication.

---

## 📌 Overview

This project simulates a secure communication system using:

- **Quantum Key Distribution (BB84 Protocol)** for unbreakable key exchange  
- **Steganography** to embed quantum keys inside images undetectably  
- **AES-256 Encryption** to encrypt messages using extracted quantum keys  

It offers quantum-safe messaging with **man-in-the-middle attack resistance**—a must-have for futuristic cyber defense.

---

## 🚀 Features

✅ Simulated Quantum Key Generation using **Qiskit**  
✅ Key Hiding via **Least Significant Bit (LSB) Steganography**  
✅ Key Extraction and Verification from Image  
✅ Message Encryption & Decryption with **AES-256**  
✅ Fully implemented in **Python** (No quantum computer required!)  

---

## 🧠 Tech Stack

- 🧪 Qiskit – Quantum key simulation  
- 🖼️ OpenCV – Image processing for steganography  
- 🔐 PyCryptodome – AES-256 encryption  
- 🐍 Python 3.8+

---

## 🧪 How It Works

1. **Generate Quantum Key:** Simulate BB84 quantum key using Qiskit  
2. **Embed Key:** Hide the quantum key in an image (LSB steganography)  
3. **Extract Key:** Recover the hidden key from image  
4. **Encrypt & Decrypt:** Use AES-256 for message security with extracted key  

---

## ⚙️ Setup

```bash
git clone https://github.com/your-username/quantum-stego-aes.git
cd quantum-stego-aes
pip install -r requirements.txt
python main.py
```
Quantum Key: 1010101010101010
Extracted Key: 1010101010101010
Encrypted: b'6ZbcN9vbN+d+LZbk6bLd0PvPpxYvku5D'
Decrypted: Confidential: QKD Project
    


