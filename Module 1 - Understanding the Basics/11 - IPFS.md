# IPFS Fundamentals

IPFS (InterPlanetary File System) is a peer-to-peer distributed file system that enables decentralized storage and sharing of files, websites, applications, and data. Unlike traditional HTTP-based systems that locate content by its location (e.g., a URL), IPFS identifies content using a unique cryptographic hash, ensuring authenticity and immutability. This content-addressed architecture is a cornerstone of IPFS's ability to create a resilient and decentralized web.

---

## **Key Concepts**

### **Content-Based Addressing**  

Files in IPFS are identified and retrieved using their Content Identifier (CID), which is derived from the file's cryptographic hash.  

### **Benefits**  
  - **Integrity Verification**: The CID allows users to verify that the content hasn't been altered since it was added to the network. Any change to the file would result in a completely different hash.  
  - **Immutable Links**: Content links are permanent, ensuring reliable references over time.
  - **Resilience**: Files are not reliant on a single server, reducing the risk of data loss.  
  - **Scalability**: As more nodes join the network, the system's capacity and performance improve. 

### **Distributed Storage**  
  IPFS divides files into smaller chunks, distributes them across participating nodes, and maintains a distributed hash table (DHT) to locate data. Popular or frequently accessed files may propagate across multiple nodes, enhancing access speed and redundancy.   

### **Implications**
  - **Censorship Resistance**: Content is not hosted on a single server, making it difficult for authorities or malicious actors to take it down.  
  - **Fault Tolerance**: Even if several nodes go offline, the content can still be accessed from other nodes.  

---

## **Use Cases**

### **Decentralized Websites**  
- Traditional websites rely on central servers, making them vulnerable to outages or attacks. Hosting websites on IPFS ensures they remain accessible even during network failures.  
- A static site hosted on IPFS can be accessed using its CID or through gateways like [https://ipfs.io/](https://ipfs.io/).

### **Blockchain Metadata Storage**  
- Blockchains like Ethereum are inefficient for storing large data files due to high costs and storage limitations.  
- Use IPFS to store large off-chain data (e.g., documents, images, or videos) while keeping a reference to the CID on-chain.  

### **Content Distribution**  
- IPFS's distributed architecture enables faster and more cost-effective sharing of large datasets, such as scientific research data or media files.  
- Streaming services, archival data systems, and educational content sharing.  

### **NFTs**  
- NFTs (non-fungible tokens) often link to metadata (e.g., artwork, videos) stored off-chain due to the size of these files.  
- Metadata stored on IPFS is tamper-proof, thanks to its content-based addressing.  
- By pinning data (using services like Pinata or Filecoin), NFT assets remain accessible indefinitely.  

### **DApps Front-End Hosting**  
- Decentralized applications (DApps) benefit from hosting their user interfaces on IPFS to ensure censorship resistance and uptime.  
- A blockchain voting app can store its smart contracts on-chain and host its front-end on IPFS.  

---

## References

- [IPFS Official Site](https://ipfs.io/)  
- [Understanding IPFS](https://docs.ipfs.io/concepts/what-is-ipfs/)  
- [Hosting a Website on IPFS](https://docs.ipfs.io/how-to/host-single-page-site/)  
- [Pinata Cloud](https://pinata.cloud/)  
- [IPFS and NFTs](https://nftschool.dev/concepts/ipfs-for-nfts/)  
- [Web3: Demystifying IPFS (InterPlanetary File System)](https://medium.com/novai-blockchain-101/web3-demystifying-ipfs-interplanetary-file-system-2f26bebd9a71)  

