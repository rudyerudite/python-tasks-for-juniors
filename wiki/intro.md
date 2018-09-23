# Cryptography
 
Ever since communication became a key instrument for exchanging ideas there was always a need to keep information safe from prying eyes and ears. Cryptography was thus invented so as to fulfill this need. Let’s explore this art further which dates back to 1900 BC and without which nothing in this world would had been secured!

## Introduction

### What is Cryptography?
The word “Cryptography” gets it roots from two greek words “cryptos” and “graphein” which when put together simply imply translating messages into a “secret language”.  In formal terms, Cryptography is the art of converting information into an unintelligible form so that no unauthorized person can understand it.

### Importance of Cryptography
Suppose you are selling your old smartphone to someone. You would surely use the “restore to factory settings” mode to erase all your personal data. But, the fact is your data can still be restored. So how do you prevent someone from accessing your personal data? One way of solving this is to change all your data to a different form (known as encryption which we’ll see later)  such that no unauthorized person can get your original data back. Cryptography is used to ensure safe storage of critical data. It is also used to secure messages over messaging apps (like Whatsapp) , phone calls and emails. Without it, people would have had a hard time protecting their data.

## What is encryption?
Encryption simply implies applying key to your plain messages in a  clever way to produce an unbreakable cipher. On the other hand, decryption implies taking encrypted text and changing it back to your plain messages.
Now, we'll try to understand some terms used in the above definition with the help of the following story.

### Ram, Sita and Crypto!
Let's go back in the ancient times and see how the use of cryptography would had made a difference then.

Ram and Sita wanted to have a secure communication between them while Sita was in Lanka. The only way for exchanging messages between them was using pigeons as message carriers. But the evil Ravana got hold of the pigeons and read all their messages.

So now both of them decided to change their message using a secret code so that even if Ravana got hold of their messages he would not understand them.This way of converting simple messages to a secretive form is known as **encryption**. A message that is converted to hidden form is known as the plaintext. The hidden form of a message is known as the **ciphertext**. The secret code that is used to convert messages to a secret form is called as **cipher**.

Now suppose Ravana is intelligent enough to understand their secret way of converting messages and somehow cracks the secret messages. So now the couple will have to think of sending their messages to each other in more secured manner.

Let’s assume that the couple had a magical box which only opened with a specific key which both of them always had with them (as dangers come without telling). So now Ram planned to lock their letters in this magical box and the pigeon would carry it to Sita. At the other end, Sita would open it with the help of the key which she has. So Ravana again would have to figure out some another way to break the secret lock and get hold of their letters.

A **key**, in cryptography, is a sequence of bits used by a cryptographic algorithm (or a kind of a cipher) to transform plain text into cipher text or vice versa. A key is usually not shared publicly. A longer key ensures a secure encryption. We will see this in the next section.

Well, in real life scenarios, our everyday communication over Internet, phone calls or any other media takes place in a similar way as explained in the above story. It is done in such a way such that no intruder can understand them or get back the original messages.

## Bruteforce: sounds like a force?

What would you do if you are given a 4-digit padlock which opens only when the entered 4 digits are right. The basic approach to break this lock would be to guess different combinations of digits so as to get the right sequence which opens the lock. 

>This way of guessing or trying out all possible ways to break an encryption is called bruteforce. 

**Key length**, as the name says, is the length of the key whereas **key space** is the possible keys available for encryption. **Message space** is the number of possible values that a plain text might be encrypted as.

If the key length and the key space of an encryption system is limited then it becomes very easy for the attacker to try out different possible keys ( as there are only a limited number to try out ) and carry out a bruteforce attack easily. Also, if the message space is limited it becomes easy for the attacker to easily guess which plain text was encrypted.
