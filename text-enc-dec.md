## Text Encryption Decryption

### Text Encrypt With Interactive Password
```sh
echo -n "That's the text"|openssl enc -e -aes-256-cbc -a
```

### Text Decrypt With Interactive Password
```sh
echo "U2FsdGVkX1/QsvpX4PNADJT3rMWAMJpPRjYOUw4kRgA="|openssl base64 -d|openssl enc -d -aes-256-cbc
```
