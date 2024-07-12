# Ccrypt
ccrypt is a command-line tool used for file encryption and decryption in Unix-like operating systems. It provides strong encryption using the Rijndael cipher (AES) with key sizes up to 256 bits.
## Installation
1. **Open Terminal and type the commands**:
   
   ```
   sudo su
   sudo apt install ccrypt
   ```

## Steps
1. **Choose a File to Encrypt**:
- **Creating a File**
  - Open the terminal.
  - Command:
    ```
    nano filename
    ```
  - Enter your text.
  - Press `Ctrl+X`, then `Y`, and `Enter` to save the file.

2. **Encryption**:
- Encrypt a file with:
  ```
  ccrypt filename
  ```
- Set a password when prompted.
- A new file with the extension `.cpt` will be created.

*Tip*: For repeated encryption, use:
  ```
  ccrypt -e filename
  ```

3. **Decryption**:
- Ensure the file to decrypt is encrypted.
- Decrypt with:
  ```
  ccrypt -d filename.cpt
  ```
- Enter the password.

*Note*: Use `cat filename` to view file contents.
