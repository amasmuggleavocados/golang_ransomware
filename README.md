# Golang Ransomware

- needed simple ransomware to test a few things and didn't trust the existing ransomware code bases on git.
- it does not delete the files it encrypts, instead it drops them in an "encrypted" directory created in the current working directory where the binary is executed from.
- code base also contains a decryption routine that will decrypt all the files found in the "encrypted" directory
- the key is static inside of the code base
