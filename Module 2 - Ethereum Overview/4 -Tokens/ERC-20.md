# **ERC-20 (Fungible Tokens)**

The **ERC-20** standard is the most widely adopted token standard on the Ethereum blockchain, enabling the creation and management of **fungible tokens**. Fungible tokens are interchangeable, meaning each unit is identical and has the same value as any other unit of the token. The ERC-20 standard ensures that tokens can interact seamlessly with wallets, decentralized applications (DApps), exchanges, and other smart contracts, fostering compatibility and interoperability within the Ethereum ecosystem.

---

## Key Features

### **1. Standardized Functions**
- ERC-20 provides a consistent and predictable interface for token implementation, ensuring all ERC-20 tokens share the same core functionality.
- These standardized functions include checking balances, transferring tokens, approving allowances, and enabling third-party token management.
- By defining these shared rules, ERC-20 simplifies development and integration across platforms.

---

### **2. Interoperability**
- **Seamless Integration**: ERC-20 tokens can be seamlessly integrated into Ethereum-based wallets (e.g., MetaMask, Trust Wallet), exchanges, and smart contracts.
- **Compatibility**: Platforms and protocols that support ERC-20 can interact with any token adhering to the standard without additional customization.
- This standardization has contributed significantly to Ethereum's ecosystem growth, enabling innovation in **DeFi** (Decentralized Finance), NFTs (Non-Fungible Tokens), and DAOs (Decentralized Autonomous Organizations).

---

### **3. Transferability**
- Tokens can be sent and received between Ethereum addresses, similar to how cryptocurrencies like Bitcoin work.
- The `transfer()` and `transferFrom()` functions enable direct transfers and programmatically approved transfers (e.g., from a smart contract).

**Example**:  
Alice can transfer 100 tokens to Bob using `transfer()` or authorize a DApp to transfer those tokens on her behalf using `approve()` and `transferFrom()`.

---

### **4. Approval Mechanism**
- ERC-20 introduces an **approval and allowance** system that allows a third party (e.g., a smart contract or an exchange) to transfer tokens on behalf of the token holder.
- This is achieved through two key functions:
  - `approve(address spender, uint256 amount)`
  - `allowance(address owner, address spender)`

**Use Case**:  
- In decentralized exchanges (DEXs), users approve the DEX smart contract to spend a specific number of tokens for trading.
- This avoids giving the DEX unlimited control over their tokens.

---

### **5. Transparency**
- The `Transfer` and `Approval` events enable the logging of token transfers and approvals on the blockchain, providing a public and immutable transaction history.
- This ensures transparency, accountability, and audibility for token holders and developers.

---

## Key Functions

### **1. Token Supply Management**
- `totalSupply()`:  
  Returns the total supply of tokens in circulation. This function ensures transparency about the maximum or circulating token supply.

---

### **2. Balance Inquiry**
- `balanceOf(address account)`:  
  Returns the token balance for a specific Ethereum address.

**Example**:  
If Bob holds 1,000 tokens in his wallet, calling `balanceOf(Bob)` will return 1,000.

---

### **3. Token Transfer**
- `transfer(address to, uint256 amount)`:  
  Transfers tokens directly from the caller's address to a recipient's address.

- `transferFrom(address from, address to, uint256 amount)`:  
  Transfers tokens on behalf of an address that has previously approved the caller to spend tokens.

**Use Case**:  
A user deposits tokens into a staking smart contract. The smart contract calls `transferFrom()` to move tokens from the user's wallet.

---

### **4. Approval and Allowance**
- `approve(address spender, uint256 amount)`:  
  Approves an address (spender) to withdraw tokens up to the specified `amount` from the token holder's balance.

- `allowance(address owner, address spender)`:  
  Returns the remaining number of tokens that the spender is allowed to transfer on behalf of the owner.

---

## Events

### **1. Transfer**
- `Transfer(address indexed from, address indexed to, uint256 value)`:  
  Emitted when tokens are transferred from one address to another.

---

### **2. Approval**
- `Approval(address indexed owner, address indexed spender, uint256 value)`:  
  Emitted when a token owner approves a spender to transfer tokens on their behalf.

---

## Use Cases

### **1. Cryptocurrencies**
- ERC-20 is widely used to implement stablecoins (e.g., USDC, USDT, DAI) and native utility tokens for blockchain ecosystems.

---

### **2. Utility Tokens**
- Many decentralized applications (DApps) use ERC-20 tokens as utility tokens to grant users access to services, discounts, or governance rights.

**Example**:  
- Tokens like **LINK** (Chainlink) are used to pay for oracle services.
- Tokens like **BAT** (Basic Attention Token) reward users and advertisers in the Brave browser ecosystem.

---

### **3. Governance Tokens**
- ERC-20 tokens allow holders to participate in decision-making processes for decentralized protocols.
- Governance tokens give users voting rights on proposals such as protocol upgrades, changes to fee structures, or allocation of treasury funds.

**Example**:  
- Tokens like **COMP** (Compound) and **UNI** (Uniswap) allow users to vote on proposals within their respective ecosystems.

---

### **4. DeFi Applications**
- ERC-20 tokens are the backbone of the decentralized finance (DeFi) ecosystem. They enable:
  - **Lending and Borrowing**: Platforms like Aave and Compound allow users to lend or borrow ERC-20 tokens.
  - **Decentralized Exchanges (DEXs)**: Platforms like Uniswap and SushiSwap facilitate token swaps.
  - **Yield Farming and Staking**: Users stake ERC-20 tokens to earn rewards.

---

### **5. Tokenized Assets**
- Real-world assets, such as real estate, stocks, or commodities, can be represented as ERC-20 tokens. This enables fractional ownership and increases liquidity for traditionally illiquid assets.

**Example**:  
- Tokenized gold (e.g., **PAXG**) allows users to hold and transfer fractional amounts of physical gold.

---

## Advantages of ERC-20

- **Standardization**: Ensures consistency across Ethereum-based tokens.  
- **Interoperability**: Widely supported by wallets, DApps, and exchanges.  
- **Liquidity**: Enables easy transfer and trading of tokens.  
- **Transparency**: On-chain data ensures trust and traceability.  
- **Programmability**: Allows for innovative use cases like automated trading, lending, and governance.  

---

## Limitations

- **Gas Costs**: High transaction fees during network congestion.  
- **Approval Model**: Requires manual approval for DApps to transfer tokens, which can be cumbersome for users.  
- **No Native Divisibility Enforcement**: Tokens are divisible by default but require developers to define decimals for precision.  

---

## References

- [ERC-20 Token Standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/)  
- [Creating an ERC-20 Token](https://ethereum.org/en/developers/tutorials/erc20-token-contract/)  
- [How to Use ERC-20 Tokens](https://consensys.net/knowledge-base/ethereum-token-standards/erc-20/)  
- [ERC-20 Explained: A Beginner's Guide](https://medium.com/novai-blockchain-101/erc-20-tokens-a-beginners-guide-to-blockchain-transactions-5e3eb4b68b1c)
