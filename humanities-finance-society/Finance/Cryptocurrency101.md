# Cryptocurrency 101

> *A cryptocurrency is a digital or virtual currency that is secured by cryptography, making it nearly impossible to counterfeit or double-spend.*

---

## The Big Picture

Historically, when you transferred money to a friend, you needed a trusted third party—a bank, a credit card company, or a platform like PayPal—to record the transaction:
- The bank maintains a private ledger (database) of who owns what.
- You trust the bank not to lose your record, edit your balance, or block your transfer.

**Cryptocurrency** was designed to eliminate the need for this trusted intermediary. 

By combining computer networking with advanced mathematics (cryptography), cryptocurrency allows a decentralized network of computers to maintain a shared, public ledger that anyone can see but no single authority can control. This is the birth of **decentralized finance (DeFi)**.

This article introduces the blockchain ledger, the role of public/private keys, consensus mechanisms, and smart contracts.

---

## The Technology: The Blockchain

All cryptocurrencies run on a database technology called a **blockchain**:

```
                       ┌─────────────────────────┐
                       │   BLOCKCHAIN STRUCTURE  │
                       └────────────┬────────────┘
                                    │
         ┌──────────────────────────┼──────────────────────────┐
         ▼                          ▼                          ▼
┌──────────────────┐       ┌──────────────────┐       ┌──────────────────┐
│     BLOCK 1      │       │     BLOCK 2      │       │     BLOCK 3      │
│ Transactions A-C │◄──────│ Transactions D-F │◄──────│ Transactions G-I │
│ Hash: 0001a3     │       │ Prev Hash: 0001a3│       │ Prev Hash: 0092b8│
│                  │       │ Hash: 0092b8     │       │ Hash: 082e1c     │
└──────────────────┘       └──────────────────┘       └──────────────────┘
```

- **Blocks:** Groups of transaction records packed together.
- **The Chain:** Each block contains a mathematical summary (a cryptographic hash) of the previous block.
- **Immutability:** Because each block is linked to the previous one, you cannot change a transaction in Block 1 without changing the math in every single block that follows it. To edit the ledger, you would have to hack thousands of computers across the globe simultaneously, making the history virtually unchangeable.

---

## Public vs. Private Keys: How You Own Crypto

To send and receive cryptocurrency, you use a **digital wallet**, which consists of two keys:

- **Public Key (Your Address):** Like your email address or bank account number. Anyone can see it, and anyone can use it to send you cryptocurrency.
- **Private Key (Your Password):** A long string of numbers and letters that gives you the power to sign transactions and spend the crypto linked to your public address. 
- **The Rule:** If you lose your private key, you lose access to your money forever (there is no "forgot password" button in decentralized finance). If someone steals your private key, they steal all your funds.

---

## Consensus Mechanisms: Reaching Agreement

Without a central bank, how does the decentralized network agree on which transactions are valid? They use **consensus mechanisms**:

- **Proof of Work (PoW):** Computers (miners) compete to solve complex mathematical puzzles. The first to solve the puzzle gets the right to add the next block to the chain and is rewarded with new cryptocurrency. This requires massive electrical power. (Used by Bitcoin).
- **Proof of Stake (PoS):** Network participants (validators) lock up a portion of their own cryptocurrency (their "stake") as collateral. The network randomly selects validators to build blocks. If a validator attempts to cheat, their stake is confiscated. This uses 99.9% less energy than PoW. (Used by Ethereum).

---

## Smart Contracts: Programmable Money

Modern blockchains (like Ethereum) allow you to run code on the ledger. These programs are called **Smart Contracts**:
- A smart contract is an agreement that executes automatically when specific conditions are met, without human intervention.
- *Example:* A smart contract could say: *"If the weather database shows it rained today, pay Farmer Bob $100 from the insurance fund."*

---

## Key Terms

- **Cryptocurrency:** A digital currency secured by cryptography.
- **Blockchain:** A decentralized, chronological database of transaction blocks.
- **Private Key:** A secret cryptographic code giving access to digital assets.
- **Public Key:** A public address used to receive digital assets.
- **Proof of Work:** A consensus mechanism based on computational puzzle-solving.
- **Proof of Stake:** A consensus mechanism based on collateral ownership.
- **Smart Contract:** Self-executing digital contracts on a blockchain.

---

## Further Reading

- Money101 — How cryptocurrency compares to traditional fiat currencies
- Bitcoin101 — The history and mechanics of the first cryptocurrency
- Finance101 — The core principles of capital allocation under uncertainty
