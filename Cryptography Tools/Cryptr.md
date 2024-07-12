# Tool1: Cryptr
A simple shell utility for encrypting and decrypting files using OpenSSL.
## Installation
```
git clone https://github.com/nodesocket/cryptr
```


## Steps to encrypt:
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
   - Run the following command:
     ```
     cryptr encrypt filename
     ```
   - Set a password when prompted.
   - A new file with the extension `.aes` will be created.

3. **View Encrypted file**:
   - To view the encrypted content, use:
     ```
     cat filename.aes
     ```
   - The encrypted file content is not human-readable.

## Steps to decrypt:
1. **Choose a File to Decrypt**:
   - Select an AES encrypted file for decryption.
     - Use `ls` in the terminal to list all files; choose any `.aes` file from the list.

2. **Decryption**:
   - Decrypt the file using:
     ```
     cryptr decrypt filename.aes
     ```
   - Enter the decryption password as required.
   - The file will be decrypted.

3. **View Decrypted file**:
   - To view the decrypted content, use:
     ```
     cat filename
     ```
   - The file content is now in a readable format.



