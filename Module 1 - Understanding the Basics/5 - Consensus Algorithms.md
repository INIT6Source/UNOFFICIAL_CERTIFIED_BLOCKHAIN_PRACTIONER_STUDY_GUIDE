# Consensus Algorithms

Consensus algorithms enable distributed systems, like blockchains, to agree on a single source of truth. They ensure that all nodes in the network maintain a consistent ledger, despite potential failures or malicious actors.

---

## Common Consensus Algorithms

### **1. Proof of Work (PoW)**
Miners solve computational puzzles to validate transactions and create new blocks.

- **Advantages**: High security due to the computational difficulty of attacks.
- **Disadvantages**: Energy-intensive and environmentally unsustainable.
- **Used By**: Bitcoin, Litecoin, and Ethereum (prior to The Merge).

---

### **2. Proof of Stake (PoS)**
Validators lock up cryptocurrency (stake) to participate in block validation.

- **Advantages**: Energy-efficient and scalable.
- **Disadvantages**: Potential for wealth concentration and centralization.
- **Used By**: Ethereum (post-Merge), Cardano, Polkadot.

---

### **3. Delegated Proof of Stake (DPoS)**
Stakeholders vote for delegates who validate transactions on their behalf.

- **Advantages**: Higher transaction throughput.
- **Disadvantages**: Increased centralization risk.
- **Used By**: Burstcoin (now Signum).

---

### **4. Proof of Elapsed Time (PoET)**
Validators are assigned a random "sleep time," and the one whose timer finishes first earns the right to produce the next block.

- **Advantages**: Fairly distributes block production without excessive energy consumption.
- **Disadvantages**: Relies on specialized hardware for generating trusted wait times.
- **Used By**: Hyperledger Sawtooth (Sawtooth Lake).

---

## Comparing PoW and PoS in Ethereum

### **1. Energy Consumption**
- **PoW**: High energy usage due to mining hardware.
- **PoS**: Significantly reduced energy consumption.

### **2. Security**
- **PoW**: Security comes from the computational work required.
- **PoS**: Security is derived from economic incentives and penalties.

### **3. Decentralization**
- **PoW**: Mining pools can lead to centralization.
- **PoS**: Lower barriers to entry may promote decentralization.

---

## References

- [Blockchain Consensus Mechanisms](https://ethereum.org/en/developers/docs/consensus-mechanisms/)
- [Understanding the Ethereum Merge](https://ethereum.org/en/upgrades/merge/)
- [Proof of Stake FAQs](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/)
- [Security Considerations of PoS](https://vitalik.ca/general/2017/12/31/pos_faq.html)
- [Delegated Proof of Stake](https://www.investopedia.com/terms/d/delegated-proof-of-stake-dpos.asp)
- [Understanding Blockchain Consensus Algorithms](https://supersimplearn.medium.com/understanding-blockchain-consensus-algorithms-6d560fe67984)
