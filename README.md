# TepeliText Secure File Converter

**Description:**
TepeliText is a secure file conversion tool that allows you to encrypt and decrypt text files using AES-256 encryption. The tool provides a simple interface for converting .txt files to encrypted .tepelitext files and vice versa, with all processing done client-side in your browser.

**Features:**
* **Military-Grade Encryption:** Uses AES-256 encryption to secure your text files
* **Client-Side Processing:** All encryption/decryption happens in your browser - no data is sent to servers
* **Secure Key Generation:** Generates strong 32-character encryption keys
* **File Integrity:** Encrypted files appear as scrambled text when opened directly
* **Cross-Platform:** Works in any modern web browser

**How to Use:**

**Encryption:**
1. **Generate or Enter Key:** Click "Generate Key" or enter your own encryption key
2. **Select File:** Choose a .txt file to encrypt
3. **Download:** The encrypted .tepelitext file will be available for download

**Decryption:**
1. **Select File:** Choose a .tepelitext file to decrypt
2. **Enter Key:** Provide the encryption key used during encryption
3. **View/Download:** View the decrypted content and download as .txt if needed

**Security Notes:**
* Always keep your encryption keys secure
* The tool does not store any files or keys
* Losing your encryption key means permanent data loss
* For maximum security, use the generated keys instead of custom ones

**Technical Details:**
* Encryption Algorithm: AES-256
* Key Length: 32 characters
* File Format: .txt ↔ .tepelitext
* Dependencies: CryptoJS for encryption

**Limitations:**
* Maximum file size limited by browser memory
* Only processes plain text files
* No password recovery mechanism

**Project Structure:**
* Single HTML file with embedded CSS and JavaScript
* Uses CryptoJS library for encryption
* No server-side components

**License:**
This project is open-source and free to use. Modify and distribute as needed.

**Disclaimer:**
This tool is provided as-is without any warranties. Use at your own risk for sensitive data.
