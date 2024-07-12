# Mcrypt
Mcrypt was a deprecated command-line tool in Kali Linux for basic file encryption using various algorithms, now superseded by more secure alternatives like OpenSSL and GnuPG.
## Installation
1. **Open Terminal and type the commands**:
   
   ```
   sudo su
   sudo apt install mcrypt
   ```
*Tip:* Type the following command to check what algorithms are used for encryption
  -Command:

```
mcrypt --list
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
- Run the following command to encrypt the file:
  ```
  mcrypt filename
  ```
- Set a password when prompted.
- A new file with the extension `.nc` will be created.

3. **Decryption**:
- Ensure the file to decrypt is an encrypted file.
- Run the following command to decrypt:
  ```
  mcrypt -d filename.nc
  ```

*Note*: Use `cat filename` to view the contents of the file.

   
