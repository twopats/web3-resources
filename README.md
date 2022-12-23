# web3-resources

This repo is a hub of useful educational resources and documentations that I found helpful on my exploration on the following topics:

- cryptography
- blockchain 
- EVM 
- history of smart contract exploits
- smart contracts security
- regenerative web3

I hope that these may serve you on your adventure as well.

### ConsenSys Resources

Consensys is a web3 powerhouse. There are many good bookmarks to leave.

[About ConsenSys](https://consensys.net/about/) 

>ConsenSys is the leading Ethereum software company. We enable developers, enterprises, and people worldwide to build next-generation applications, launch modern financial infrastructure, and access the decentralized web. Our product suite, composed of Infura, Quorum, Truffle, Codefi, MetaMask, and Diligence, serves millions of users, supports billions of blockchain-based queries for our clients, and has handled billions of dollars in digital assets. Ethereum is the largest programmable blockchain in the world, leading in business adoption, developer community, and DeFi activity. On this trusted, open source foundation, we are building the digital economy of tomorrow.

https://github.com/muellerberndt/smashing-smart-contracts/blob/master/smashing-smart-contracts-1of1.pdf
https://github.com/ConsenSys/mythril

---

### Formal Verification (of EVM smart contracts)

https://ethereum.org/en/developers/docs/smart-contracts/formal-verification/

---
### History of reentrancy-attacks 

https://github.com/pcaversaccio/reentrancy-attacks

A community effort to record past EVM reentrancy attacks. Consider that theDAO hack that led to the only hardfork of Ethereum capitlized on reentrancy vulnerabilities. That did not stop following reentrancy vulnerabilities from showing on contracts post theDAO incident. Also worth noting that these vulnerabilities follow a recognizable pattern that can be detected through static analysis of the source code or tracing of the contract bytecode in formal-verification.

---

### Auditor Roadmap 

https://github.com/Quillhash/QuillAudit_Auditor_Roadmap

Interested in becoming an auditor? Even if you're not,  this roadmap visualization is a pretty informative mapping of how tools and different knowledge play different parts in the decentralized ecosystem.

---

### Solidity 0.8.17 Breaking Changes

https://docs.soliditylang.org/en/v0.8.17/080-breaking-changes.html

In my experience, this documentation is very neat to have. I have gone through the ethernaut challenges and other walkthroughs. Outdated guides may use outdated versions of the Solidity compiler. It serves well to identify syntactical differences.
