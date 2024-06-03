---
layout: post
title:  Cryptography in Cybersecurity
date:   2024-06-04 12:00:00 +0000
categories: jekyll update
usemathjax: true
---

Below is an example of cryptography in cybersecurity.

Any page needing cryptography should start with the frontmatter:
{% highlight markdown %}
usecryptography: true
{% endhighlight %}

### Symmetric Key Cryptography
Symmetric key cryptography, also known as secret key cryptography, uses the same key for both encryption and decryption. This means both the sender and the receiver must share a common secret key.

#### Example
Plaintext: HELLO
Key: 3
Ciphertext: KHOOR

In this example, each letter in "HELLO" is shifted by 3 positions in the alphabet to produce the ciphertext "KHOOR".

### Asymmetric Key Cryptography
Asymmetric key cryptography, also known as public key cryptography, uses a pair of keys – a public key and a private key. The public key is used for encryption, while the private key is used for decryption. This eliminates the need to share a common secret key.

#### Example
Public Key: (e, n)
Private Key: (d, n)

If Alice wants to send a secure message to Bob, she uses Bob's public key to encrypt the message. Bob then uses his private key to decrypt the message.

### Hash Functions
Hash functions take an input (or 'message') and return a fixed-size string of bytes. The output, known as a hash value or digest, appears random. Hash functions are designed to be one-way functions, meaning it should be infeasible to reverse the process and obtain the original input from the hash value.

#### Example
Input: "Hello, World!"
Hash: "a0b65939670bc28f5b0f68fc0d9e6a41"

Hash functions are used in various applications, including verifying data integrity and storing passwords securely.

### Applications of Cryptography in Cybersecurity
#### Secure Communications
Cryptography ensures secure communication over the internet. Protocols such as HTTPS use cryptographic algorithms to encrypt data transmitted between a user's browser and a web server, protecting it from eavesdropping and tampering.

#### Data Integrity
Cryptographic hash functions are used to verify the integrity of data. For example, software developers often provide checksums alongside their software downloads. Users can compute the checksum of the downloaded file and compare it to the provided checksum to ensure the file has not been tampered with.

#### Authentication and Authorization
Cryptography is crucial in authentication and authorization processes. Digital signatures, for example, use asymmetric cryptography to verify the authenticity and integrity of a message, software, or digital document.

#### Secure Storage
Sensitive data, such as passwords and personal information, are often stored in an encrypted format. Even if unauthorized individuals gain access to the storage medium, they cannot read the encrypted data without the decryption key.

The above is accomplished with thanks to various cryptographic experts and cybersecurity professionals who have contributed to the field.

