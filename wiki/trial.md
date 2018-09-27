**HASH FUNCTIONS**

A cryptographic hash function takes a message of any size as plaintext and gives out a fixed-sized string as ciphertext. The ciphertext, is an alphanumeric string (containing both letters and numerals) and is called a DIGEST.
![Picture](https://github.com/nsg1999/Images/blob/master/hash%20intro-1.png)

In hash functions, no key is used. It is also known as one-way process as it is impossible to get the original message back once the hashing operation is applied to the message. 
Message Digest(MD) and Secure Hash (SHA) are some of the popular hash functions.
For example,
Using a MD5 hash, “**a**” can be written as “**0cc175b9c0f1b6a831c399e269772661**”
Amazing! Isn’t it? But one thing to be noted is that the md5 hash is not an ENCRYPTION. It is just a fingerprint of your input.
Similarly, using a SHA256 hash generator, we can get “**a**” as “**87428FC522803D31065E7BCE3CF03FE475096631E5E07BBD7A0FDE60C4CF25C7**”.
![Picture](https://github.com/nsg1999/Images/blob/master/sha-1%20example-1.png)

Every hash output is unique for a unique input and is the same for same input. But, it is possible for the hash function to give the same result for two different inputs.
As mentioned before, hash functions are one-way functions, it is practically impossible to reverse them, hence, can be used to generate passwords which are really strong.
Even though the generated hashes are really strong, there are a plenty of online tools available to crack the hashes, CrackStation being one of them.


