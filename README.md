# Secret Notes Manager

This Python script uses Tkinter to create a simple application for managing secret notes. It provides functionality to encrypt and decrypt text-based notes using a master key.

The functions `encode()` and `decode()` handle the encryption and decryption processes respectively. `encode()` takes a given key and text, then encrypts the text using a simple algorithm and base64 encoding. `decode()` reverses this process, decrypting the encoded text using the same key.

**The application has two main functionalities:**
- `save_and_encrypt_notes()`: Takes user inputs for title, secret message, and a master key. It encrypts the message and saves it along with the title into a file named "mysecret.txt".
- `decrypt_notes()`: Retrieves an encrypted message from the text area along with the master key. It decrypts the message and displays the original content in the text area.

The graphical interface includes entry fields for the title, secret message, and master key. Users can save encrypted notes or decrypt previously encrypted messages.

**Note:** Proper input validation is not extensively implemented here, so it's important to input the correct master key when decrypting to retrieve the original content.
