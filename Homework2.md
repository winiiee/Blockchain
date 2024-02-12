# 1)What is mining? Why it is important in the field of blockchain?

In Bitcoin, mining simply means validating and verifying the Bitcoin transactions. And after validations, blocks are added to the ledger.

It is very important in the field of blockchain technology because of the following reasons:

**a)Transactions validation and block creation**

Decentralization is a core concept of blockchain technology. Different transactions are verified and validated by miners by solving complex mathematical problems and after verifications block is added to the public ledger.

At first, miners collect transactions into blocks and compete to solve complex mathematical problems. Once it is solved, they create a new block of validated transactions and add them to the blockchain.

**b)Security and decentralization**

The mining process includes different consensus mechanisms like proof of work and the decentralized nature of mining makes it even more secure.


# 2)What is a block and list out the elements inside the block?**

A block can be said as a list of ordered records.

A set of transactions that have been validated before being added to the blockchain

The elements inside the block are as follows:

**a)Transaction**

Contains a collection of verified transactions (transactions made by users such as sending and receiving bitcoins)

**b)Hash**

     Previous block hash

     Current block hash

**c)Timestamp**

**d)Nounce**



# 3)What are Nonce and Target in blockchain mining?**

**Nonce** (number used only once)

a number used by miners when they try to create a block in a blockchain network like Bitcoin.

**How it works?**

At first, the nonce value is generated randomly when a block is created. (nonce + block’s data hashed together to produce an output)

if the output hash meets the target set by the system then the block is valid.

**Wait what’s a target???**

Difficulty level set for miners to find the “ **valid block hash** “

a simple analogy 

Think like the difficulty level set for the game we play (hard, medium, easy)

miners are like the players in a game trying to solve a problem or a puzzle. Their task is to find a unique number (nonce)  when combined with other information within the block produces a special code called hash that meets the difficulty level set by the system.

If it meets the conditions specified by the system, the block becomes valid.

if not, the nonce is changed, and the block is re-hashed until the valid output is found.

(if the hash doesn’t meet the target, nonce is changed and the block is re-hashed with the new nonce value.)

Miners compete to find the valid nonces that satisfy the target set by the system.
