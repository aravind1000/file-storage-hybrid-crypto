# 🔐 File Storage Using Hybrid Cryptography

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-WebApp-black?logo=flask)
![Security](https://img.shields.io/badge/Security-AES%20%2B%20RSA-green)

---

## 📌 Overview

This project implements a **secure file storage system** using **Hybrid Cryptography**, combining the strengths of both **symmetric (AES)** and **asymmetric (RSA)** encryption techniques.

It ensures:

* 🔒 High-level data security
* ⚡ Fast encryption/decryption
* 🛡 Protection against unauthorized access

---

## 🚀 Features

* 🔐 **Hybrid Encryption (AES + RSA)**
* 📂 **Secure File Upload & Storage**
* ✂️ **File Splitting Mechanism**
* 🔄 **File Reconstruction**
* 🔓 **Decryption Pipeline**
* 🌐 **Web Interface using Flask**
* 📁 Organized file handling (raw, encrypted, restored)

---

## 🧠 How It Works

1. User uploads a file via web interface
2. File is split into multiple parts
3. AES encrypts file data
4. RSA encrypts AES key
5. Encrypted data stored securely
6. During retrieval:

   * RSA decrypts AES key
   * AES decrypts file
   * Parts are merged back

---

## 🛠️ Tech Stack

* **Language:** Python
* **Framework:** Flask
* **Cryptography:** AES, RSA
* **Frontend:** HTML, CSS
* **Libraries:** PyCryptodome / Cryptography

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/aravind1000/file-storage-hybrid-crypto
cd file-storage-hybrid-crypto
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv myenv
source myenv/bin/activate   # Linux/Mac
myenv\Scripts\activate      # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Application

```bash
python app.py
```

### 5️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

## 🔐 Security Highlights

* AES ensures **fast and secure data encryption**
* RSA secures **key exchange mechanism**
* Hybrid model prevents **key exposure risks**
* File splitting adds **extra layer of security**

---
