Introducing_Ethereum_and_Solidity_Notes.md

----
# 1

https://puu.sh/waag0/79e2db5de2.png


Symmetric Encryption: both parties must have the same key.

Asymmetic cryptography:
  - don't trust the channel of communication
  - each person has a PAIR of different, but mathematically related keys
    - Public key cryptography: wartime communications
    - 'computational complexity involved in encrypting the data makes it useful only for small data objects, like the alphanumeic string that becomes your private key'


Symmetric Encryption:
  - Bob and Alice has the same encryption key.
  - It is used to encrypt a message, and decrypt the ciphertext output.

Asymmetric encryption:
  - Public Key: can list on website
    - public keys are used to send message / encrypt info
  - Private key: 
    - private keys are used to decrypt info

Secure Messaging: 
  - Alice encrypts using Bob's public key.
  - Bob decrypts using his matching private key.
  Secure, BUT, anyone could send a message claiming to be Alice.

Secure and Signed Message:
  - Encrypt Alice's plaintext message using her private key.
  - Then Encrypt it again using Bob's public key.
  - When Bob receives, he decrypts using his private key.
  - He must decrypt using Alice's public key.
    - Assures that Alice is the one that originally encrypted using her private key.

Public <> Private, corresponding to
  Q: Is it true that public keys and private keys have the property that ONE can be used to decrypt messages encrypted by the other, and vice-versa?

-----------

If Alice were to only encrypt her plaintext using her own private key, then anyone with her public key could decrypt it. "Open Message Format".  (for leaks/info dumps, etc.)

Digital Signature:
  - Alice hashes plaintext of her message
  - Attach it along with message
  - Encrpyt bundle with own private key.
  - Encrpyt bundle with Bob's public key.

  - When Bob decrypts the ciphertext he can run Alice's plaintext message through the same hashing algorithm Alice used. 
  - Ensures that the message can't be modified, because of the additional step of 
  [HashedPlaintext + Plaintext]

Pretty important to mining.
--------



# 2 - The Mist Browser
mist, applications


------

# 3 - The EVM
how the EVM works

------


# 4 - Solidity Programming
how to build things
  - develop contracts that compile to EVM bytecode
    - edge out serpent
    -LLL (lisp)
    - Mutan(deprecated)
  - Enables you to move tokens of value in any ethereum based system
  - Private groups altered, re-released, and deployed the source code (Ch11)

------


# 5 - Smart Contracts and Tokens
- Smart contracts are reusable classes...bid system, section bid system, polling system...
  - Secure IM system...
  ???


------


# 6 - Mining Ether
  - understand how mining works, so you can point your rigs at new cryptocurrencies in the future


------


# 7 - Cryptoeconomics Survey
- hashing vs encryption
- we need to defend our public networks from attackers...

------

# 8 - Dapp Deployment
  - running blockchain based applications >>> managing clients in a cloud-hosted paradigm

  - hub-and-spoke webapps scale vertically, reflecting the load of a sever
    - ETH apps scale horizontally...

  -components of the protocol will mature, things are limited now but will get faster

Prototyping Areas:
  - accounting system for something in the real world, or for other contracts
  - create forwarding contracts, such as a savings account that resends income to a separate bucket automatically
  - manage a relationship between several parties, such as freelancer agreement or payroll
  - act as a software library for other contracts
  - act as controllers for other systems or sets of contracts
  -serve as application-speciifc logic for a communal web service
  -serve as a utility that developers can use on a single-serving basis, such as a random number generator
------

# 2 - Creating Private Chains
  - they have merit as learning tools
  - may have uses for large corps, identity, etc

  - Why blockchains are not better for all dbs and networks


  - Trustworth chains: lots of proof of work.

  - creating your blockchain genesis file...

------

# 9 - Use Cases*****


------

# 10 - Advanced Concepts***
  - Private groups altered, re-released, and deployed the source code (Ch11)

------

# 11 - Backmatter*?

------

------
------
------



# (ROLLING) TODOs:
  - eth.guide
  - Review etherium roadmap.


VB - Proof of stake design philosophy:
https://medium.com/@VitalikButerin/a-proof-of-stake-design-philosophy-506585978d51#.7n3x85gvs


- Address typo: Main PAge of ch8.