#Block Cipher Mode of Encryption

Block Cipher Mode of Encryption is a symmetric  mode of encryption that is applied on fixed size of the **plain text**. This size is called the **block-size**. Block size can be of any length but a larger block size is preferred to prevent any possible ‘dictionary attacks’. The block size is also generally taken to be a multiple of 8 as it becomes easy to operate upon. 

The plain text that is to be encrypted is taken and is divided into different blocks depending upon the block-size. The last block is usually padded, as described later, if it’s size not the same as the size of the block.

Each block is encrypted separately and is operated upon by a **symmetric encryption key** which actually governs the strength of the encryption. The operation performed would depend on the encryption scheme chosen as discussed later. Hence, the resultant cipher text, that is obtained after encryption, is of the same size as the original plain text. 

Here’s a ![diagrammatic explanation of the same.](https://github.com/rudyerudite/python-tasks-for-juniors/blob/master/Block%20Ciphers.png "Block cipher") 

Now, we’ll see the different ways of data encryption under block ciphers.
1. **Advanced Encryption Standard**:  successor to DES algorithm and is the most widely in  use
2. **Data Encryption Standard**:  considered insecure because of it’s small key size of 56 bits.
3. **Triple Data Encryption Standard**: developed mainly to counter the drawbacks of DES.

##Modes of Encryption

Different modes of encryption are basically **different algorithms**  which can be applied on the different ways of data encryption for block ciphers. This means that mode of encryption defines how each plain text block can individually be encrypted. Here are the most commonly used modes of encryption,

###ECB

####What is ECB?

**E**lectronic **C**ode **B**ook (or **ECB**) mode of encryption is the simplest of all the modes of encryption. This mode of encryption is the first one which was implemented under AES. But, later we’ll analyze the plus and the minus features of this mode because of which it’s popularity is reduced. Now, we’ll see how is ECB mode of encryption is applied to any of the above described data encryption algorithm.

####How is the encryption done?

In this mode of encryption the plain text is divided into different blocks of equal block sizes. Then each block is encrypted in parallel. The following is a ![diagrammatic representation of the same.](https://github.com/rudyerudite/python-tasks-for-juniors/blob/master/601px-ECB_encryption.svg.png "ECB encryption")

As you can see the different blocks of the plain text are encrypted separately using any of the  algorithms described above (Like AES, DES) The parallel encryption of each block is the basic essence of the ECB  mode.

####How is decryption done?

Similar to the encryption the cipher text is divided into different blocks depending upon the block size. Thus, decryption is done on each block, at the same time, using the algorithm with which it was encrypted. Here’s a ![diagrammatic representation of the same.](https://github.com/rudyerudite/python-tasks-for-juniors/blob/master/601px-ECB_decryption.svg.png) 

####Advantages of ECB

The advantage of ECB mode of encryption over others is that here each block is encrypted separately. Therefore, if any of the block goes corrupted it doesn’t affect the rest of the encryption. Also, because of this feature a multiprocessor can simultaneously encrypt different blocks thus saving time.

####Disadvantages of ECB

The main disadvantage of ECB is that the similar part of the plain text are encrypted with the same key to the same cipher text. That is, if in block 1 the plain text character ‘e’ is encrypted as ‘f’ in block 2 also if there’s ‘e’ in the plain text it would be encrypted as ‘f’. Also, the blocks of cipher text can be rearranged which when decrypted would give deranged output which is undesirable.

####Vulnerabilities of ECB

The most common attack on ECB is the “ECB byte at a time attack” which exploits the loophole in ECB encryption which would give the same cipher text when applied to the similar characters of plain text.
