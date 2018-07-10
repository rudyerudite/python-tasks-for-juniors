#Transposition Ciphers

In transposition ciphers the characters of the plaintext are changed without any change in their identity. That is, in case of transposition cipher the units of the plaintext are rearranged in some order according to some algorithm.

Let’s see an example of transposition cipher:

#####Route Cipher:
Suppose we have this sentence: **THE ENEMY IS CLOSE**. So, this could be written in the following pattern:
T E M S O
H N Y C S
E E I L E

And this would be encrypted along the “route” as specified in the encryption key. So if the order (as given by the key) is followed along the left side to the right for each line then it’s encrypted as *TEM SOHNY CS EEILE* .Insecure routes often leak away important parts of the message thereby breaking the encryption. Hence, it was not widely used or used with another cipher.

Just like how substitution ciphers can be broken with the help of frequency analysis of each letter in the cipher text similarly transposition ciphers can be broken too! This is done with the help of similar method of frequency analysis of the adjacent letters like bi-grams or the tri-grams which may help to identify the algorithm which has been used to do the transposition. 

