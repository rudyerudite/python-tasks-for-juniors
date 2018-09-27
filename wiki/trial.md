From simple character shifts to involving complex math theorems cryptography went through a lot of stages. The roots of cryptography are very deep. All started with Julius Caesar who tried to secure the messages he sent. So let’s dig back the past to get familiar with cryptographic evolution.

Cryptography is classified into (according to the time)
* Classical Cryptography
* Modern Cryptography

Caesar Cipher is an example of classical cryptography as it involved manipulating the characters of the message. Whereas the present modern cryptography is based on computer algorithms, number theory etc. Previous article mentions the classification of Modern Cryptography as follows
* Symmetric Key Cryptography
* Asymmetric Key Cryptography

### Symmetric Key Cryptography
We know that symmetric key cryptography is a simplest way of encryption dependent upon a single randomly generated key. Larger key space is required for it to be secure. Popular examples for symmetric key cryptography is DES, AES etc.
AES is found to be advantageous over DES, as the key size of AES is double to that of DES.

> **_Think Once:_** How can sender and receiver exchange the key securely over an insecure network?

Trouble with Symmetric Key Crypto is that, sharing a key becomes difficult over a insecure channel. This led to the rise of Asymmetric Key Cryptography. 

### Asymmetric Key Cryptography
Asymmetric Crypto is highly secure when compared to Symmetric Crypto because it uses separate keys for encryption and decryption. Secrecy in private key is the reason for its security. It also includes generating large numbers and making mathematical operations with them. Popular examples are RSA, DLP etc

RSA is the most popular public key cryptosystem and its security is based on factorisation of a large integer whereas security of DLP is based on calculating the discrete logarithm of a large number. 

Though Asymmetric Crypto is found to be advantageous over Symmetric Crypto, it has its own set of disadvantages. It is expensive and takes a lot of time to compute. Hence, Elliptical Curve Cryptography is gaining popularity over RSA as it is faster as well as efficient. Also the sizes of keys are smaller making it advantageous over the other crypto systems. 

Crypto has a lot of scope in future as the communication through computer systems increases, the need for security and encryption systems increases. From evolution to creating revolution Crypto went through a long path and is still exploring different origins. Above all security is the main motive.
