# Smart Contracts

Smart contracts are programs stored on a blockchain that execute automatically when predetermined conditions are met. They facilitate, verify, and enforce the negotiation of agreements without the need for intermediaries.

---

## **Characteristics**

**Immutable**: Cannot be changed once deployed.  
**Transparent**: Code is visible to all participants, promoting trust.  
**Self-Executing**: Automate processes when conditions are satisfied.  
**Trustless**: Eliminates the need for a central authority.  

---

## **Components**

**Functions**: Perform specific actions.  
**Visibility**: Defines access scope (public, private, internal, or external).  
**State Variables**: Store data permanently on the blockchain.  
**Modifiers**: Alter the behavior of functions, e.g., access control.  
**Events**: Logs that can be captured by off-chain applications.  

---

## **Development Languages**

[**Solidity**](https://soliditylang.org/): Similar to JavaScript, supports inheritance, libraries, and complex user-defined types.  
[**Vyper**](https://docs.vyperlang.org/en/stable/#): Pythonic language aimed at simplicity, emphasizing security and auditability.  

---

## **Development Tools**

[**Remix IDE**](https://remix.ethereum.org): Online editor for writing and testing smart contracts.  
[**Truffle Suite**](https://archive.trufflesuite.com/): Framework for development, testing, and deployment.  
[**Hardhat**](https://hardhat.org/): Development environment with debugging and testing features.  

---

## **Common Vulnerabilities**

**Reentrancy Attacks**: Exploits recursive calls.  
**Integer Overflows/Underflows**: Errors in numeric calculations.  
**Access Control Issues**: Unauthorized access to functions.  

---

## **Best Practices**

**Audit Contracts**: Regularly review code for vulnerabilities.  
**Use Safe Math Libraries**: Prevent numeric calculation errors.  
**Follow Design Patterns**: Implement patterns like [Checks-Effects-Interactions](https://fravoll.github.io/solidity-patterns/checks_effects_interactions.html) to mitigate risks.  

---

## **References**

- [Smart Contracts Explained](https://ethereum.org/en/smart-contracts/)  
- [Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/)  
- [Ethereum Smart Contract Security](https://ethereum.org/en/developers/docs/smart-contracts/security/)  
- [What are Smart Contracts: Your Gateway to Ethereum’s Realm](https://medium.com/novai-blockchain-101/smart-contracts-your-gateway-to-ethereums-digital-realm-80ebb514617a)  
