# Consensus Algorithms

Consensus algorithms enable distributed systems, like blockchain, to agree on a single source of truth. They ensure that all nodes in the network maintain a consistent ledger, despite potential failures or malicious actors.

---

## **Proof of Work (PoW)**
Miners solve computational puzzles to validate transactions and create new blocks.

- **Advantages**: High security due to the computational difficulty of attacks.
- **Disadvantages**: Energy-intensive and environmentally unsustainable.
- **Used By**: Bitcoin, Litecoin, and Ethereum (prior to The Merge).

---

## **Proof of Stake (PoS)**
Validators lock up cryptocurrency (stake) to participate in block validation.

- **Advantages**: Energy-efficient and scalable.
- **Disadvantages**: Potential for wealth concentration and centralization.
- **Used By**: Ethereum (post-Merge), Cardano, Polkadot.

---

### **Delegated Proof of Stake (DPoS)**
Stakeholders vote for delegates who validate transactions on their behalf.

- **Advantages**: Higher transaction throughput.
- **Disadvantages**: Increased centralization risk.
- **Used By**: Burstcoin (now Signum).

---

### **Proof of Elapsed Time (PoET)**
Validators are assigned a random "sleep time," and the one whose timer finishes first earns the right to produce the next block.

- **Advantages**: Fairly distributes block production without excessive energy consumption.
- **Disadvantages**: Relies on specialized hardware for generating trusted wait times.
- **Used By**: Hyperledger Sawtooth (Sawtooth Lake).

---

### **Proof of Authority (PoA)**
Validators are pre-approved and rely on their reputation to validate transactions and produce new blocks.

- **Advantages**: High efficiency and scalability, making it suitable for private or consortium blockchains.
- **Disadvantages**: Limited decentralization due to reliance on a small group of validators.
- **Used By**: HVeChain, xDai
---

## Comparing PoW and PoS in Ethereum

### **Energy Consumption**
- **PoW**: High energy usage due to mining hardware.
- **PoS**: Significantly reduced energy consumption.

### **Security**
- **PoW**: Comes from the computational work required.
- **PoS**: Derived from economic incentives and penalties.

### **Decentralization**
- **PoW**: Mining pools can lead to centralization.
- **PoS**: Lower barriers to entry may promote decentralization.

---

## References

- [Blockchain Consensus Mechanisms](https://ethereum.org/en/developers/docs/consensus-mechanisms/)
- [Understanding the Ethereum Merge](https://ethereum.org/en/upgrades/merge/)
- [Proof of Stake FAQs](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/)
- [Delegated Proof of Stake](https://www.ledger.com/academy/what-is-delegated-proof-of-stake-dpos)
- [Understanding Blockchain Consensus Algorithms](https://supersimplearn.medium.com/understanding-blockchain-consensus-algorithms-6d560fe67984)
- [Proof of Elapsed Time](https://www.investopedia.com/terms/p/proof-elapsed-time-cryptocurrency.asp)
- [Proof of Authority](https://www.coindesk.com/learn/what-is-proof-of-authority)