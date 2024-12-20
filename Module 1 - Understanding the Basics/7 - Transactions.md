# Transactions

Transactions are the actions that change the state of the blockchain. They can involve transferring cryptocurrency between accounts or invoking smart contracts. Once included in a block and confirmed, transactions become part of the immutable ledger.

---

## **Key Components**

**Sender Address**: The account initiating the transaction.  
**Receiver Address**: The account receiving funds or data.  
**Amount**: The quantity of cryptocurrency being transferred.  
**Gas Fee**: A unit representing computational effort.  
**Gas Price**: The cost per unit of gas, often in Gwei.  
**Gwei**:  
- 1 Gwei = 1,000,000,000 Wei (the smallest unit of Ether, analogous to how a penny is a fraction of a dollar).  
- 1 Ether = 1,000,000,000 Gwei.  

**Total Fee**: Gas used multiplied by the gas price.  
**Nonce**: A counter that represents the number of transactions sent from an address.  
**Signature**: Digital signature created using the sender's private key.  
**Data Field**: Contains additional data, such as function calls to smart contracts.  

---

## **Transaction Lifecycle**

1. **Creation**: User prepares the transaction with necessary details.  
2. **Signing**: Transaction is cryptographically signed by the sender.  
3. **Broadcasting**: Sent to the network and enters the mempool.  
4. **Validation**: Nodes verify the transaction's authenticity and correctness.  
5. **Block Inclusion**: Miners/validators include the transaction in a new block.  
6. **Confirmation**: The block is added to the blockchain, confirming the transaction.  
7. **Finality**: After several confirmations, the transaction is considered irreversible.  

---

## **Gas Mechanics**
**EIP-1559 Upgrade**: Introduced a dual fee model with a base fee and priority fee 
- **Base Fee**: Adjusts dynamically based on network congestion.  
- **Priority Fee (Tip)**: Optional fee to incentivize miners/validators.  

**Gas Limit**: The maximum amount of gas the sender is willing to consume.  
**Out of Gas Error**: Occurs when the gas limit is insufficient for the transaction execution.  

---

## **References**

- [Ethereum Transactions](https://ethereum.org/en/developers/docs/transactions/)  
- [Understanding Gas and Fees](https://ethereum.org/en/developers/docs/gas/)  
- [Etherscan Transaction Tutorial](https://etherscan.io/txs)  
- [How to Read Ethereum Transactions and Logs](https://rylezhou.medium.com/how-to-read-ethereum-transactions-and-logs-80f2892f6b52)  
- [EIP-1559: Fee Market Change](https://eips.ethereum.org/EIPS/eip-1559)  
- [Demystifying Blockchain Transactions](https://medium.com/novai-blockchain-101/demystifying-blockchain-transactions-c3bea3877ba5)  
