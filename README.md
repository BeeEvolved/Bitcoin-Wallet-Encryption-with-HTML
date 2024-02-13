
<p align="center">
  <img src="https://github.com/BeeEvolved/Bitcoin-Wallet-Encryption-with-HTML/blob/main/encrypt.jpg" alt="Project Logo">
</p>


# Bitcoin-Wallet-Encryption-with-HTML
🔐 Encrypt and Decrypt Bitcoin wallet files using HTML and WebCrypto API and SHA-256 "Same as Bitcoin". Secure your wallet data with password protection. A lightweight and user-friendly tool for securing your Bitcoin. 
# Bitcoin Wallet Encryption with HTML



### Coffee Tips--> BTC: 1P6gz8bggna5s93th9CxNommxcNivN2bPp 


This project provides a simple HTML-based tool for encrypting and decrypting Bitcoin wallet files. The encryption is done using the WebCrypto API, allowing users to secure their wallet data with a password.

## Table of Contents
- [Features](#features)
- [How to Use](#how-to-use)
  - [Encryption](#encryption)
  - [Decryption](#decryption)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)

## Features

- **File Encryption**: Encrypt Bitcoin wallet files using AES-GCM encryption. Encrypt Bitcoin Wallet with HTML can encrypt your Wallet or SEED in various file types, including plain text files (.txt), documents (Word, PDF, Excel, etc.), images (JPEG, PNG, GIF, etc.), archives (ZIP, TAR, RAR, etc.
- **Password Protection**: Secure the encrypted file with a user-provided password.
- **File Decryption**: Decrypt the encrypted wallet file using the same password.
- **Uses SHA-256 same Algo that secures Bitcoin**: In this code, SHA-256 (Secure Hash Algorithm 256-bit) is employed as a critical component of the password-based key derivation process. When a user enters a password, it is converted into a fixed-size hash using SHA-256. This hash then serves as the basis for key generation through the PBKDF2 (Password-Based Key Derivation Function 2) algorithm. The strength of SHA-256 lies in its cryptographic properties, including resistance to collisions and its one-way nature, making it computationally infeasible to reverse the process and obtain the original password. By utilizing SHA-256 in the key derivation process, the code enhances the security of the encryption mechanism, as it ensures that the resulting cryptographic key is derived from a securely hashed version of the user's password, adding an extra layer of protection to the Bitcoin wallet encryption process.
- **Things that can go wrong**:     Brute Force Attacks: Attackers could attempt to guess the strong password through brute force attacks. Although a strong password reduces the likelihood of success, brute force attacks can still be attempted, especially if the password has a vulnerability.

    ⚠️Password Sniffing: If the password is transmitted over an insecure channel, such as an unsecured Wi-Fi network, it could be intercepted using packet sniffing techniques.

    ⚠️Code Modification: The HTML and JavaScript code stored on a server or in public storage might be susceptible to tampering. If an attacker gains access to the code, they could modify it to capture passwords or leak sensitive information.

    ⚠️Social Engineering: Even with a strong password, users might still be susceptible to social engineering attacks, where attackers manipulate individuals into revealing their passwords or sensitive information.

    ⚠️Server Compromise: If the server hosting the HTML and JavaScript code is compromised, attackers could gain access to the stored strong passwords or modify the code for malicious purposes.

    ⚠️Lack of Secure Communication: If the communication between the user and the server is not secure (e.g., using HTTPS), attackers might intercept and manipulate the data, compromising the security of the password.

    ⚠️Key Management Issues: If the system lacks proper key management practices, such as secure generation and storage of cryptographic keys, it could introduce vulnerabilities even if the password is strong.

    ⚠️Cryptographic Weaknesses: While the provided code uses AES-GCM, the implementation might have vulnerabilities, and the lack of security audits increases the risk of potential weaknesses.

    ⚠️Zero-Day Exploits: If there are unknown vulnerabilities (zero-days) in the encryption or decryption logic, attackers could exploit them without the knowledge of the system owner..

## How to Use

### Encryption

1. Select a wallet file (.txt) using the provided file input.
2. Enter a password and repeat it for confirmation.
3. Click "Encrypt file" to generate an encrypted HTML file.

### Decryption

1. Open the generated encrypted HTML file.
2. Enter the password used for encryption.
3. Click "Decrypt file" to retrieve the original wallet file.

## Requirements

- A modern web browser with support for the WebCrypto API.

## Contributing

Feel free to contribute to the development of this project. If you find any issues or have suggestions, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).MIT License

Copyright (c) 2024 Bee Evolved

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Disclaimer

This software is provided "as-is" and is experimental and educational in nature. It is not intended for real-world use and should not be used to handle actual Bitcoin transactions or store sensitive information. The creators and contributors of this project disclaim any responsibility for any potential loss, damages, or security vulnerabilities that may arise from the use of this.

**Use at Your Own Risk:**
This software is distributed in the hope that it will be useful for educational purposes, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. The use of this software is entirely at your own risk.

**Educational Purpose Only:**
This project is designed to serve as an educational resource and should not be considered a secure solution for handling real Bitcoin assets. It is recommended to use established and secure methods for handling cryptocurrency transactions.

By using this software, you acknowledge and accept the risks associated with experimental and educational software. If you have any concerns or uncertainties, it is advisable to seek professional advice before using this tool.

The creators and contributors of this project reserve the right to modify, update, or discontinue this software at any time. Your use of this software constitutes your acceptance of these terms.

