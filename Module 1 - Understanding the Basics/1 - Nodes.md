# Nodes

Nodes serve as the foundation of blockchain networks. They're individual computers or devices that participate in the network by maintaining, validating, and broadcasting the distributed ledger. Nodes work collaboratively, ensuring the integrity, security, and the synchronization of the blockchain, making it decentralized and resilient against failure and attack.

---

# **Full Nodes**

Full nodes store the entire history of the blockchain, including all blocks and transactions since the genesis block.

## **Features**

- **Complete Ledger Maintenance**: Download and verify every block and transaction, ensuring they comply with the consensus rules.
- **Independent Validation**: Independently validate transactions and blocks without relying on external sources.
- **Consensus Enforcement**: Enforce the network's consensus rules, rejecting invalid blocks and transactions.

## **Examples**

- **Bitcoin Core**: The reference implementation for the Bitcoin network.
- **Geth (Go Ethereum)**: A widely used Ethereum client that can operate as a full node.

---

# **Light Nodes**

Light nodes download only the block headers instead of the entire blockchain, relying on full nodes for data.

## **Features**

- **Reduced Storage Requirements**: Require significantly less disk space and bandwidth.
- **Faster Sync Times**: Quickly synchronize with the network.
- **Dependence on Full Nodes**: Rely on full nodes to retrieve transaction data and validate blocks.

## **Examples**

- **Mobile Wallets**: Lightweight wallets on smartphones, such as Trust Wallet.
- **Web3 Browsers**: Browsers like MetaMask that allow interaction with DApps.

---

# **Miner/Validator Nodes**

Miner/validator nodes are specialized nodes responsible for creating new blocks and securing the network.

## **Features**

- **Block Production**: Propose and add new blocks to the blockchain.
- **Consensus Participation**: Actively participate in the consensus mechanism, e.g., Proof of Work (PoW), Proof of Stake (PoS).
- **Earning Rewards**: Receive cryptocurrency rewards for their services.

## **Examples**

- **Bitcoin Miners**: Use computational power to solve PoW puzzles.
- **Ethereum Validators**: Stake ETH to validate transactions in PoS.

---

# **Importance**

- **Decentralization**: Distribute the ledger across many participants, preventing central points of failure.
- **Security**: Independently verify transactions, reducing the risk of fraud.
- **Network Health**: Ensure reliability, availability, and resistance to attacks.

---

## References

- [Ethereum Nodes and Clients](https://ethereum.org/en/developers/docs/nodes-and-clients/)
- [Bitcoin Core](https://bitcoincore.org/en/about/)
- [Running an Ethereum Node](https://geth.ethereum.org/docs/getting-started)
- [Understanding Full Nodes](https://bitcoin.org/en/full-node)
- [Hyperledger Fabric Peer Nodes: A Beginner’s Guide](https://medium.com/@supersimplearn/what-is-hyperledger-fabric-peer-nodes-a-beginners-guide-f55ec2ca8d81)
