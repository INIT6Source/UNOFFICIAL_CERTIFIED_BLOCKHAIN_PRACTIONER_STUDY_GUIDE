# **Beacon Chain**

The Beacon Chain is a core component of Ethereum 2.0, introduced to implement the Proof of Stake (PoS) consensus mechanism. Launched on December 1, 2020, it runs in parallel to the original Ethereum PoW chain and coordinates the network of validators, manages the PoS protocol, and lays the groundwork for future scalability improvements like sharding.

---

## **Functions**

- **Consensus Layer**:  
  Manages the PoS protocol, ensuring validators reach consensus on the state of the blockchain.  

- **Validator Management**:  
  Handles the registration, activation, and removal of validators, along with stakes and rewards.  

- **Randomness Source**:  
  Provides secure randomness (RANDAO) for validator selection and sharding assignments.  

- **Sharding Coordination**:  
  Will oversee the implementation and synchronization of shard chains in future upgrades.  

---

## **Technical Details**

### **1. Slots and Epochs**
- **Slot**: A 12-second period during which a validator can propose a block.  
- **Epoch**: Consists of 32 slots (~6.4 minutes). At the end of each epoch, the chain finalizes and applies rewards and penalties.  

### **2. Finality**
- **Justification and Finalization**:
  - Uses Casper FFG (Friendly Finality Gadget) to achieve finality.
  - Once a block is finalized, it cannot be reverted unless a significant portion of validators are penalized.

---

## **Validator Participation**

### **1. Staking Requirements**
- Minimum of **32 ETH** staked to become a validator.  

### **2. Responsibilities**
- Propose new blocks when selected.  
- Attest to blocks proposed by others.  

### **3. Rewards and Penalties**
- **Rewards**: Earned for active participation in block proposal and attestation.  
- **Penalties**:  
  - **Inactivity Leak**: Penalized for being offline.  
  - **Slashing**: Penalized for malicious behavior such as double-signing or equivocating.

---

## **References**

- [The Beacon Chain](https://ethereum.org/en/upgrades/beacon-chain/)  
- [Ethereum 2.0 Specs](https://github.com/ethereum/eth2.0-specs)  
- [Understanding The Merge](https://ethereum.org/en/upgrades/merge/)  
- [Staking on Ethereum](https://ethereum.org/en/staking/)  
- [Beaconcha.in Explorer](https://beaconcha.in/)  
- [Eth2 Book – Mastering Ethereum 2.0](https://eth2book.info/)  
