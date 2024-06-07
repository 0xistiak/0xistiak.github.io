---
title: Cryptography in Cybersecurity Old Two Up
date: 2024-05-01 00:00:00 +0000
# modified: 2024-05-02 00:00:00 +0000
tags: [cybersecurity, stego]
description: all about crypto.
# image: "/dir/file.png"
---
<hr>
Below is an example of cryptography in `cybersecurity.` he website was made using Jekyll the one of open source static sites generator, and using my own simple theme.
<hr>

<figure>
<img src="/cryptography/header.png" alt="cryptography">
<figcaption>Fig 6. evaluasi shell dari tahun ke tahun.</figcaption>
</figure>

### Any page frontmatter:

```
usecryptography: true
```

### Symmetric Key Cryptography
`Symmetric`  key <a href="http://en.wikipedia.org/wiki/List_of_terminal_emulators" target="_blank" rel="noopener">cryptography</a>, also known as secret key cryptography, uses the same key for both encryption and decryption. This means both the sender and the receiver must share a common ~~[cybersecurity]~~  secret key.

#### Example
```
# without bash py
Plaintext: HELLO
Key: 3
Ciphertext: KHOOR
```
In this example, each letter in "HELLO" is shifted by 3 positions in the alphabet to produce the ciphertext "KHOOR".

### Asymmetric Key Cryptography
<img src="/cryptography/terminal_nginx.gif" alt="cryptography">
Asymmetric<sup id="asymmetricc">[[1]](#asymmetricc-ref)</sup> key cryptography, also known as public key cryptography, uses a pair of keys – a public key and a private key. The public key is used for encryption, while the private key is used for decryption. This eliminates the need to share a common secret key.

#### Example
```ex
# with custom
Public Key: (e, n)
Private Key: (d, n)
```

```bash
# with bash py
# Referencing its directory.
$ python /foo/bar

# It's equivalent to this.
$ python /foo/bar/__main__.py
```

If Alice wants to send a secure message to Bob, she uses Bob's public key to encrypt the message. Bob then uses his private key to decrypt the message.

### Hash Functions
Hash functions take an input (or 'message') and return a fixed-size string of bytes. The output, known as a hash value or digest, appears random. Hash functions are designed to be one-way functions, meaning it should be infeasible to reverse the process and obtain the original input from the hash value.

#### Example
Input: "Hello, World!"
Hash: "a0b65939670bc28f5b0f68fc0d9e6a41"

Hash functions are used in various applications, including verifying data integrity and storing passwords securely.

### Example Table overflow-table

<div class="overflow-table" markdown="block">

| Markdown                | HTML                               |    Rendered Output    |
| :---------------------- | :--------------------------------- | :-------------------: |
| `[Example Link](#link)` | `<a href="#link">Example Link</a>` | [Example Link](#Link) |
| `_Be Italic_`           | `<em>Be Italic<em/>`               |      _Be Italic_      |
| `**Be Bold**`           | `<strong>Be Italic<strong/>`       |      **Be Bold**      |

</div>

\*) _resize to see difference_

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

##### Notes

<small id="asymmetricc-ref"><sup>[[1]](#asymmetricc)</sup> peraa blablabla jhrkj jkhret.</small>

##### Resources

- [Evolution shells in Linux](http://developer.ibm.com/tutorials/l-linux-shells/)
- [Kernel Defintion](http://www.linfo.org/kernel.html)
- [The Shell](http://www.cis.rit.edu/class/simg211/unixintro/Shell.html)