# File Encryptor
### Overview
Parallel File Encryptor is a C++ application that encrypts and decrypts files using parallel processing to improve performance. The tool utilizes multithreading to handle large files efficiently.

### Features
- Parallel Encryption/Decryption: Leverages multithreading to speed up the process.
- AES Encryption: Uses AES-256 encryption for secure file handling.
- Cross-Platform: Compatible with Windows, macOS, and Linux.

### Requirements
- C++11 or later
  
### Installation
1. Clone the repository:
```sh
https://github.com/Supsource/File-Encryptor
```
2. Build
```
make
```

### Usage
#### Encrypting a File
```
./encryptor -e -i inputfile -o outputfile -k key
```
#### Decrypting a File
```
./encryptor -d -i inputfile -o outputfile -k key
```
- '-e': Encrypt mode
- '-d': Decrypt mode
- '-i': Input file
- '-o': Output file
- '-k': Encryption key

#### Contributing
Contributions are welcome! Please submit a pull request or open an issue for any improvements or bug fixes.





