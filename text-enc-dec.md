## Text Encryption Decryption

* #### Text Encrypt With Interactive Password
```sh
echo -n "That's the text"|openssl enc -e -aes-256-cbc -a
```

* #### Text Decrypt With Interactive Password
```sh
echo "U2FsdGVkX1/QsvpX4PNADJT3rMWAMJpPRjYOUw4kRgA="|openssl base64 -d|openssl enc -d -aes-256-cbc
```

* #### Text Encrypt Command Line Password
```sh
echo -n "That's the text"|openssl enc -e -aes-256-cbc -a -k "MySuperPassword"
```

* #### Text Decrypt Command Line Password
```sh
echo "U2FsdGVkX18tLihnkrrk2lE/lz4FzPMRUToYQjfCL8s="|openssl base64 -d|openssl enc -d -aes-256-cbc -k "MySuperPassword"
```

