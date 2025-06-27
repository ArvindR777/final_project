AESCRYPT
An AES-based GUI application for file encryption and integrity verification

===========================================
Secure File Storage System with AES-256
===========================================

Cryptolocker is a simple and secure local file storage application built using Python, PyQt5, and the cryptography library.  
It allows users to encrypt and decrypt files securely using AES-256 in CBC mode and verifies file integrity using SHA-256 hashes.

-----------------------
🔐 Features:
-----------------------
- AES-256 encryption and decryption (CBC mode)
- Manual entry for Key and IV (Initialization Vector)
- File upload and secure storage with `.enc` extension
- Metadata storage (original filename, timestamp, SHA-256 hash)
- File integrity verification before decryption
- User-friendly GUI built with PyQt5

-----------------------
🖼️ Screenshots:
-----------------------
1. **Home Interface**  
   - Main window with options to upload, encrypt, and decrypt files

2. **File Upload & Encryption**  
   - Select file, enter key/IV, and perform encryption

3. **Decryption & Verification**  
   - Checks file hash before decrypting to detect any tampering

4. **Metadata View**  
   - Displays details like filename, encryption time, and hash

-----------------------
🛠️ Tools & Technologies:
-----------------------
- Python 3.x
- PyQt5 (for GUI)
- cryptography (for AES)
- hashlib (for SHA-256 hash)
- os, json, datetime (for file and metadata handling)

-----------------------
🚀 How to Run:
-----------------------
1. Install dependencies:
   pip install -r requirements.txt

2. Run the application:
   python main.py

-----------------------
📁 File Structure:
-----------------------
- main.py                  → Main application script
- ui/                      → PyQt5 UI files or layouts
- encrypted_files/         → Directory to store encrypted files
- metadata.json            → Stores metadata for encrypted files
- requirements.txt         → Python dependencies

-----------------------
🔒 Note:
-----------------------
- Ensure that you securely store your encryption key and IV.  
  Without them, decryption is not possible!
- Hashes are used to verify if the file was tampered with after encryption.



