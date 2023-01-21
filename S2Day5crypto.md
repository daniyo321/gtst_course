## Cryptography

```
S2Day5crypto.md
```

#### recall

# LAST TIME

# TOPICS


#### Topics

```
● What is Cryptography?
● Types of Cryptography
● Terms of Cryptography
● Kinds of Cryptography
● Tools
● Python for Crypto
● Obfuscation
```

#### What is Cryptography?

###### ● Cryptography is the science of secret, or hidden writing

###### ● Crypto => Hidden/Secret | Graphy => Writing

###### ● Used to secure your data/text.

###### ● It has two main Components:

```
a. Encryption
i. Practice of hiding messages so that they can not be read by
anyone other than the intended recipient
b. Authentication & Integrity
i. Ensuring that users of data/resources are the persons they
claim to be and that a message has not been altered
```

#### Encryption

**Cipher**

```
● Cipher is a method for encrypting messages
● Encryption algorithms are standardized & published
● The key which is an input to the algorithm is secret
● Key : is a string of numbers or characters
● If same key is used for encryption & decryption the algorithm is called
symmetric
● If different keys are used for encryption & decryption the algorithm is
called asymmetric
```

#### Symmetric Algorithms

● Algorithms in which the key for encryption and
decryption are the same are Symmetric
○ Example: Caesar Cipher
● Types:
○ Block Ciphers
■ Encrypt data one block at a time (typically
64 bits, or 128 bits)
■ Used for a single message
○ Stream Ciphers
■ Encrypt data one bit or one byte at a time
■ Used if data is a constant stream of
information


#### Substitution Ciphers

##### Caesar Cipher

Caesar Cipher is a method in which each letter in the alphabet is rotated by

three letters as shown


#### ...


##### Substitution Cipher

##### Using a key to shift alphabet

```
● Obtain a key to for the algorithm and then shift the alphabets
○ For instance if the key is word we will shift all the letters by four and remove the
letters w, o, r, & d from the encryption
● We have to ensure that the mapping is one-to-one
○ no single letter in plain text can map to two different letters in cipher text
○ no single letter in cipher text can map to two different letters in plain text
```

```
Website: rot13.com
```
Replacing the letters by 1 shift

we can get different rotations. To

do this we can use this website.

This encoding is called rot

encoding


#### Limitation

###### ● Any exposure to the secret key compromises

###### confidentiality of ciphertext

###### ● A key needs to be delivered to the recipient of the coded

###### message for it to be deciphered

```
○ Some intruders can get the key and BOOM! No secret
anymore.
```

#### Exercise 1

1. Change “Pass1233” text to caesar Cipher
2. What is the starting alphabet to produce “Rexler” text by shifting
3. What is the encoding method of “Rexler”
    a. Answer: Rot__
4. Change “Hello There” to cipher with a key to alphabet shift of
    “HACK”


##### Asymmetric Encryption

● Uses a pair of keys for encryption

```
○ Public key for encryption
○ Private key for decryption
```
● Messages encoded using public key can only be decoded by the private key

```
○ Secret transmission of key for decryption is not required
■ Public key can be exposed so, if i need to send you a message i just ask you for
your public key and i will encrypt the message with your public key. When you
get the ciphertext you can decrypt it with your private key.
○ Every entity can generate a key pair(private&public) and release its public key
```

#### Types of asymmetric enc.

```
● Two most popular algorithms are RSA & El Gamal
● RSA
○ Developed by Ron R ivest, Adi S hamir, Len A delman
○ Both public and private key are interchangable
○ Variable Key Size (512, 1024, or 2048 bits)
○ Most popular public key algorithm
○ It have a maths formulas for generating the keys.
● El Gamal
○ Developed by Taher ElGamal
○ Variable key size (512 or 1024 bits)
○ Less common than RS
```

#### 3 Terms of Cryptography

```
1) Encoding/ decoding
a) This is a method of creating Cipher text with our using any key
b) This can be done by doing math on the given input/substitution
i) Examples: base64,base32,rot...
2) Encrypting/Decrypting
a) This is method of creating Cipher text with keys.
b) To decrypts this kind u need to have the private key
i) Example: DES,AES,RSA
3) Hashing
a) This is a method of creating Cipher text with respect to a created hash
b) To reverse the hash, you just search for some match, you don't
decrypt/decode it.
c) Salt: is a random string used for data modification for password protection.
i) Example: MD5,sha254,...
```

#### Kinds of encodings/encryptions

```
● Base2 01100010 01110010 01100101 01100001 01101011 01101001
01110100
● Base8 142 162 145 141 153 151 164
● Base16 62 72 65 61 6b 69 74
● Base32 MJZGKYLLNF2A====
● Base58 4jP4KDubX
● Base62 22udqyscMu
● Base64 YnJlYWtpdA==
● Base85 @WH$gCM@k
● Base91 %zmfv;:YH
● URL encode: hello%20there%20%3F
● Md5: 5d41402abc4b2a76b9719d911017c
● Sha1: aaf4c61ddcc5e8a2dabede0f3b482cd9aea9434d
● Rot : Uryyb, Frphevgl Grfgref => look for some random word that looks rotated
```

#### tools

● There are lots of encodings/encryption

● To identify this we will need some

```
tools/sites
```
● Tools:

```
○ hashid
■ hashid <hash>
○ Cyber chef (web)
```

#### ...

● Goto google and
type cyberchef
● Click on the 1st link.


#### ...

● Search for magic
● Drag and drop it, to the
recipe.


#### ...

● Add your text to the input
● Look at the output it is the
guess of what the hash can be


#### decoding/decrypting

There are so, many way to reverse some hashes/ciphers.

```
● Hashes
○ Craskstation.net(non-salted)
○ Own cracking(google the name)
● Encodings
○ CyberChef
```

#### Crackstation


#### Own pages

By searching the hash type you
can get the decoder/decrypter.


#### also ...

Searching the hash is Good


#### Cyber chef

By searching any encryption you
can decode/decrypt it.

```
● We use from to decrypt
● We use to to encrypt
```

#### Exercise 2

```
1) What is the hashing algorithm of this text
“aaf4c61ddcc5e8a2dabede0f3b482cd9aea9434d”
2) What is the decoded text of
“SGVsbG8sIFNlY3VyaXR5IFRlc3RlcnM=”
3) What is the decoded text of
“KUZFM2TELBFHAZCINNTVMR2WPJSEOVTZMN3T2PI=”
4) What is the decrypted text of
“21232f297a57a5a743894a0e4a801fc3”
```

#### Python for cryptography

```
● We can use programming to do tools that can do our own encryption and
encoding hash type
● There are so many methods, even you can do the encoding/decodeing for the
base64...
● You just need to understand the maths.
● Now i will show u simple XOR’ing example
○ What is XOR?
```

#### Pseudo code





#### output


#### test

### Let’s write it by our own to understand it

### correctly.


#### Exercise 3

1. Write a program that accepts a phone number, then encode it by
    multiplying the phone number by 123456. Also do the decoder
       a. Accepts only 251... numbers dot accept 09...
2. Do the caesar cipher algorithm with python
a. Accept 1 numbers(string msg )
b. 1 variable for the storing the changed value
c. Iterate with the message accepted
i. For every string change it to unicode decimal and add 3 to it
ii. Then change the unicode decimal to character
iii. Add the character to the storing variable
d. Display the changed variable
i. “The encoded Text is: ... “


#### Base64 decode/encode


#### Obfuscation

```
● In software development, obfuscation is the act of creating source or machine
code that is difficult for humans or computers to understand.
● As we know High level programming lang. are easy to understand, so if hackers
got your code he can read it, but to make it more difficult we use this technique
● This was the code obfuscated
```

#### ...

My python code obfuscated

```
Website:
https://pyobfuscate.com/pyd
```

#### CLASS IS OVER

1. Ask question
2. DO the note(read more)
3. PRACTICE PRACTICE PRACTICE


