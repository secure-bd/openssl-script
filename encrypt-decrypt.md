### OpenSSL Encryption and Decryption
#### [Tutorial ](https://wiki.openssl.org/index.php/Command_Line_Utilities)

```sh
openssl des3 -in file.txt -out encrypted.txt
openssl des3 -d -in encrypted.txt -out normal.txt

openssl aes-256-ecb -in unen.txt -out en.txt
openssl aes-256-ecb -d -in en.txt -out unen.txt
```
#### Encrypt with AES:
```sh
aescrypt -e -p password  file.jpg
````

#### Decrypt:
```sh
aescrypt -d -p password file.jpg.aes
```

### gnupg:

```sh
To encrypt: gpg -c filename

To decrypt: gpg filename.gpg
```
