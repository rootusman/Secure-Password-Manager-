# Password-Manager-



A simple and secure password management tool built with Python, using the `cryptography` library for encryption. This project allows users to store, encrypt, and retrieve passwords for various services.



## Features

- **Key Management**:
  - Generate and save encryption keys.
  - Load existing keys for decryption.
  
- **Password Storage**:
  - Securely store passwords in an encrypted file.
  - Support for adding and retrieving passwords.

- **Encryption**:
  - All passwords are encrypted using the `Fernet` encryption mechanism from the `cryptography` library.

---

## File Overview

- **`pass_manager.py`**:
  The main script implementing the password manager functionalities, including encryption and decryption logic.

---

## Requirements

- Python 3.7 or higher
- `cryptography` library (install using `pip install cryptography`)


