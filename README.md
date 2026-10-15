# research-papers
A curated list of papers that i have read/implemented, some are still beyond my comprehension skill :( or maybe I am too lazy -- distributed systems, databases, blockchain, ml etc...

## Table of Contents
1. [Distributed Systems](#1-distributed-systems)
2. [Databases](#2-databases)
3. [Blockchain](#3-blockchain)
4. [Machine Learning](#4-machine-learning)

---

## 1. Distributed Systems

### The Google File System (2003)
**Paper:** [gfs-sosp2003.pdf](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)

### CAP Theorem
**Paper:** [Brewer's Conjecture and the Feasibility of Consistent, Available, Partition-Tolerant Web Services (2002)](https://users.ece.cmu.edu/~adrian/731-sp04/readings/GL-cap.pdf)
**Follow-up:** [CAP Twelve Years Later: How the "Rules" Have Changed (2012)](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed/)

### In Search of an Understandable Consensus Algorithm: Raft (2014)
**Paper:** [raft.pdf](https://raft.github.io/raft.pdf)

### Time, Clocks, and the Ordering of Events in a Distributed System (1978)
**Paper:** [time-clocks.pdf](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)

Defines the "happened-before" relation and introduces logical (Lamport) clocks for ordering events in systems with no global clock.

---

## 2. Databases

### ACID Properties
**Paper:** [Principles of Transaction-Oriented Database Recovery (1983)](https://dl.acm.org/doi/10.1145/289.291)
**Background:** [The Transaction Concept: Virtues and Limitations (1981)](https://jimgray.azurewebsites.net/papers/thetransactionconcept.pdf)

### Concurrency Control
**Paper:** [On Optimistic Methods for Concurrency Control (1981)](https://dl.acm.org/doi/10.1145/319566.319567)
**Paper:** [A Critique of ANSI SQL Isolation Levels (1995)](https://arxiv.org/abs/cs/0701157)

---

## 3. Blockchain

### Bitcoin: A Peer-to-Peer Electronic Cash System (2008)
**Paper:** [bitcoin.pdf](https://bitcoin.org/bitcoin.pdf)

Proposes a decentralized digital currency that prevents double-spending without a trusted third party. Transactions are recorded in a chain of blocks secured by proof-of-work, and the longest chain is the agreed history. It is the foundation of modern blockchain systems.

### Solana: A New Architecture for a High Performance Blockchain (2017)
**Paper:** [solana-whitepaper.pdf](https://solana.com/solana-whitepaper.pdf)

Introduces **Proof of History (PoH)**, a verifiable delay function that serves as a cryptographic clock. Nodes can agree on the order and time of events without heavy communication. Combined with a Proof-of-Stake consensus, it targets very high transaction throughput.

---

## 4. Machine Learning

### Efficient Memory Management for Large Language Model Serving with PagedAttention (2023)
**Paper:** [arXiv:2309.06180](https://arxiv.org/abs/2309.06180)

### An Introduction to Transformers
**Paper:** [arXiv:2304.10557](https://arxiv.org/pdf/2304.10557)
