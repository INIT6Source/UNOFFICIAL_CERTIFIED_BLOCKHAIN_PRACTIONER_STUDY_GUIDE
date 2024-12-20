# ERC-20 (Fungible Tokens)

The ERC-20 standard is the most widely adopted token standard on the Ethereum blockchain, enabling the creation and management of fungible tokens. Fungible tokens are interchangeable, meaning each unit is identical and has the same value as any other unit of the token. The ERC-20 standard ensures that tokens can interact seamlessly with wallets, decentralized applications (DApps), exchanges, and other smart contracts, fostering compatibility and interoperability within the Ethereum ecosystem.

---

## **Key Features**

### **Standardized Functions**
- Provides a consistent interface for token implementation, ensuring all ERC-20 tokens share the same core functionality.
- Includes functions for balance checks, transfers, and approvals for third-party management.

---

### **Interoperability**
- **Seamless Integration**: Works with wallets like MetaMask and Trust Wallet, and platforms like Uniswap.  
- **Compatibility**: Adheres to a standard that ensures uniform integration with Ethereum-based protocols.

---

### **Transferability**
- Enables direct token transfers and programmatically approved transfers.  
- Functions like `transfer()` and `transferFrom()` allow efficient movement of tokens across accounts.

---

### **Approval Mechanism**
- Allows a third party (e.g., a smart contract) to transfer tokens on behalf of a user.  
- Uses functions like `approve()` and `allowance()` for authorization and checks.

---

### **Transparency**
- Events like `Transfer` and `Approval` log transactions and approvals on-chain, ensuring auditable and immutable transaction histories.

---

## **Key Functions**

### **Token Supply Management**
- `totalSupply()`: Returns the total token supply.

### **Balance Inquiry**
- `balanceOf(address account)`: Returns the token balance of a given address.

### **Token Transfer**
- `transfer(address to, uint256 amount)`: Transfers tokens from the caller to another address.
- `transferFrom(address from, address to, uint256 amount)`: Transfers tokens on behalf of an authorized address.

### **Approval and Allowance**
- `approve(address spender, uint256 amount)`: Approves an address to spend tokens.  
- `allowance(address owner, address spender)`: Checks the remaining tokens a spender is authorized to transfer.

---

## **Events**

### **Transfer**
- `Transfer(address indexed from, address indexed to, uint256 value)`: Logs token transfers between addresses.

### **Approval**
- `Approval(address indexed owner, address indexed spender, uint256 value)`: Logs approvals for third-party token transfers.

---

## **Use Cases**

### **Cryptocurrencies**
- Stablecoins like **USDC**, **USDT**, and **DAI** rely on the ERC-20 standard for efficient transfer and storage.

### **Utility Tokens**
- Tokens like **LINK** (Chainlink) enable access to blockchain oracles and services.

### **Governance Tokens**
- Examples include **COMP** (Compound) and **UNI** (Uniswap), allowing holders to participate in protocol decisions.

### **DeFi Applications**
- Used in lending platforms (Aave, Compound) and decentralized exchanges (Uniswap, SushiSwap).

### **Tokenized Assets**
- Represent real-world assets like gold (**PAXG**) or real estate.

---

## **Advantages**

- **Standardization**: Ensures consistency across tokens.  
- **Interoperability**: Supported widely across Ethereum-based platforms.  
- **Transparency**: Public transaction logs foster trust.  
- **Programmability**: Enables advanced use cases like automated rewards and governance.  

---

## **Limitations**

- **High Gas Costs**: Transactions can be expensive during peak network activity.  
- **Approval Friction**: Requires users to manually approve DApps for transfers.  
- **Precision Complexity**: Developers must define decimal settings for divisibility.  

---

## **References**

- [ERC-20 Token Standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)   
- [ERC-20 Explained: A Beginner's Guide](https://medium.com/novai-blockchain-101/erc-20-tokens-a-beginners-guide-to-blockchain-transactions-5e3eb4b68b1c)  
