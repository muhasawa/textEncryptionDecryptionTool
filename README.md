
readme_content = """# Web-Based Text Encryption & Decryption Tool

A lightweight, responsive, and secure single-page web application designed for real-time text encryption, decryption, and encoding. This project was developed as an Information Security assignment to demonstrate the practical application of classical ciphers, modern symmetric cryptography, and data representation techniques.



## Features

### Core Capabilities
* **Plaintext Encryption:** Instantly transform readable text into secure ciphertext.
* **Robust Input Validation:** Prevents empty submissions and ensures an algorithm is selected before executing code.
* **Single-Page Architecture:** Smooth, client-side execution requiring zero page reloads.

### Advanced & Bonus Features
* **Bidirectional Decryption:** Full support for reversing operations back to plain text when provided with the correct key.
* **Multi-Algorithm Selection:** Built-in options spanning from classical cryptography to modern industrial standards.
* **One-Click Copy to Clipboard:** Integrated utility button to quickly copy output ciphertexts for external transmission.

---

## Cryptographic Implementations

The application supports three distinct methods of data handling:

1.  **AES (Advanced Encryption Standard)**
    * *Type:* Modern Symmetric Block Cipher.
    * *Details:* Implemented via the robust `CryptoJS` engine. It securely encrypts strings using a user-defined passphrase/secret key, rendering data computationally infeasible to breach.
2.  **Caesar Cipher**
    * *Type:* Classical Substitution Cipher.
    * *Details:* Shifts character coordinates along the standard 26-letter English alphabet based on an integer value provided in the Key field. Includes full boundary wrapping handling (e.g., 'z' wraps back to 'a').
3.  **Base64 Encoding**
    * *Type:* Data Representation Scheme.
    * *Details:* Converts text into a visual string of 64 printable ASCII characters. *Note: Used for safe data transmission, not absolute cryptographic confidentiality.*

---

## Tech Stack & Dependencies

* **Frontend UI:** Semantic HTML5, Vanilla CSS3 (Custom Grid/Flex properties, Fixed Navigation Layout).
* **Core Logic:** Client-side JavaScript (ES6+).
* **Cryptographic Library:** [CryptoJS v4.1.1](https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.1.1/crypto-js.min.js) (Loaded securely via CDN).

---

## Installation & Usage

Because this utility relies entirely on client-side compilation, running it requires zero backend configuration or package installations. 

### Running Locally
1. Clone this repository or copy the file contents:
