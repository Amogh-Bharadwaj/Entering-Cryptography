# Entering-Cryptography

Cryptography to the common man will probably just mean encrypting a message or making a message seem like rubbish to anyone except an intended recipient. But it is so much more than that. Indeed, hiding information is the ultimate goal but there are a lot of sub-fields to be understood in order to facilitate encryption.
Cryptography consists of:
1) Cryptology: The science aspect of crypto. The math behind the algorithms, application of formulae etc.
2) Cryptanalysis: Deals with the working of encryption systems. Aims to either secure them or break them.

Both cryptology and cryptanalysis are of utmost relevance when diving in here.

## Ciphers, Cryptosystems and Others:
Your primary goal is to understand the modern, popular cryptosystems in use, how these cryptosystems outdid their predecessors and what exactly makes them secure enough to be used today. Apart from cryptosystems, there are other things to know as well.
The most important topics to be thorough with are:

### 1) Public Key Cryptography and RSA:
In my opinion, the most simple to understand, fun yet and important and secure cryptosystem is the idea of public key cryptography and in particular, RSA. It involves encryption in the form of basic modular exponentiation and yet is virtually infeasible to break, given the appropriate parameters are chosen. 

### 2) Block Ciphers:
A cipher which encrypts data 1 block at a time.
The common names here are AES, DES, triple DES etc. AES(Advanced Encryption Standard) is currently the most secure encryption system ever known and hence the most trusted. It is important to know the history behind it and the gradual weathering of DES(Data Encryption Standard) which necessitated the design of AES.

### 3) Stream ciphers:
A cipher which encrypts data 1 digit of plaintext at a time.
It is important to know the difference between a stream and block cipher and when each one is applicable. 

### Diffie-Hellman and Elgamal:
They are very important key exchange systems. Like RSA, they involve a public key.

### Elliptic Curve Cryptography:
A heavily mathematical field, yet extremely effective. It is intimidating to learn but is certainly worth the study. It makes use of a mathematical Weierstrauss equation. 

### 4) Hashes :
A function which takes in data and gives out something random but of a fixed size, and is virtually impossible to reverse.Again, a big area to cover here. You would definitely want to be aware of the good hash algorithms and what makes them good(Example: SHA family of hashes), and the bad hash algorithms and what makes them bad (Example: MD5). 

### 5) PRNGs: 
A very relevant part of our subject. Many encryption systems rely on the pseudorandom generators or PRNGs. PRNGs also need to be "secure", where "secure" here would denote unpredictable. 

## Attacks
The other half of the coin, and the most exciting part of crypto as a whole: cracking an encryption. A key aspect of understanding how something is secure, is by understand why it isn't insecure.
Every encryption system has itself tested by attacks and exploits. The cryptosystems I've mentioned above each have certain exploits waiting to rip them apart if a naive lad implements them even slightly incorrectly.
When it comes to hashes, the race is always on to find collisions, breaking the hash function. 
It is also fun to see some real world effects here and companies suffering due to clever mathematical attacks on cryptosystems.

# Resources
First, I would say pick a good book to learn the theory from. Mine and many others' choice would be `Introduction to Mathematical Cryptography by Jeffrey Hoffstein`. Another valuable mention is `A Graduate Course in Applied Cryptography.Authors: D.Boneh, Victor Shoup`.
Once that's more or less done, I would highly suggest making yourself home at cryptohack.org. As a driven member of its amazing community, I can guarantee that it's the best place to learn crypto. cryptopals.com is also a good shout.
Lastly, you can elevate yourself by taking part in Capture The Flags(CTFs). That is a topic on its own so I'll just guide you to ctf101.org for more information.

Have fun ^_^





