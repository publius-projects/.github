# **Publius Project**

**Institutional governance for on-chain organisations.**

The Publius Project is the organisation dedicated to the development, maintenance, and evolution of the **Powers protocol**. We build trustless, role-based governance infrastructure that allows decentralized organisations to move beyond simple token-voting and into complex, institutional frameworks.

## **🏛️ The Powers Protocol**

Powers v0.4 (and beyond) provides the architecture for the **Rule of Mandate**. Unlike traditional governance systems that rely on monolithic voting, Powers allows a single decision to travel along multiple stakeholders through modular, asynchronous, and trustless governance paths.

### **Core Philosophy**

* **Rule of Mandate**: Actions are executed through role-restricted contracts called *mandates*. These mandates define exactly who can do what, and under what conditions.  
* **Separation of Powers**: Distribute decision-making across roles to create checks and balances—similar to legislative, judicial, and executive branches.  
* **Minimalistic Core**: The protocol is designed to be lean. Any complexity (timelocks, weighted votes, staking) is integrated through modular mandates rather than bloated core logic.  
* **Accountability**: Every action is logged and can be challenged, ensuring that devolved responsibilities remain accountable to the community treasury.

## **📂 Key Repositories**

The Publius Project ecosystem is split into three primary pillars:

### **1\. [Powers Solidity Protocol](https://www.google.com/search?q=https://github.com/publius-project/powers/tree/main/solidity)**

The core smart contracts. Includes the Powers.sol protocol, Mandate.sol base classes, and various implementations:

* **Executive Mandates**: For calling external functions and managing treasury assets.  
* **Electoral Mandates**: For assigning and managing roles within the organisation.  
* **Async Mandates**: For multi-step, conditional governance paths.

### **2\. [Frontend dApp](https://www.google.com/search?q=https://github.com/publius-project/powers/tree/main/frontend)**

A Next.js application designed to interact with Powers organisations. It provides interfaces for:

* Deploying new organisations and constitutions.  
* Interacting with specific mandates.  
* Proposing and voting on on-chain actions.

### **3\. [Documentation & Litepaper](https://powers-docs.vercel.app/welcome)**

Comprehensive guides for developers and architects:

* [Powers Protocol Guide](https://powers-docs.vercel.app/for-developers/powers)  
* [Mandate Implementation Guide](https://powers-docs.vercel.app/for-developers/mandate)  
* [Deploying your Organisation](https://powers-docs.vercel.app/for-developers/deploy-your-powers)

## **🛠️ Use Cases**

Powers enables governance patterns that solve common on-chain challenges:

* **Devolved Responsibilities**: Create accountable working groups or grants councils that manage specific domains without risking the entire treasury.  
* **Institutional Upgrades**: Gradually transition existing organisations to role-based governance without abandoning established structures.  
* **Complex Checks & Balances**: Require a proposal from one role, a veto window for another, and execution by a third.

## **🤝 Contributing**

We welcome contributions to the "Rule of Mandate." Whether you are a security researcher, a frontend developer, or a governance architect, we value your input.

1. Explore the [issues](https://www.google.com/search?q=https://github.com/publius-project/powers/issues) in our main repository.  
2. Review our [Solidity implementations](https://www.google.com/search?q=https://github.com/publius-project/powers/tree/main/solidity/src).  
3. Join the conversation regarding on-chain institutional design.

## **📜 License & Security**

All Publius Project code is distributed under the **MIT License**.

*Note: The current protocol (v0.4) is a proof-of-concept. While it has undergone internal review and community testing, it should be used with caution in production environments.*

### **Acknowledgements**

The Powers protocol represents a significant evolution in role-based governance, building upon the foundational work of OpenZeppelin, the Hats Protocol, and the generous support of contributors from the Arbitrum DAO and RnDAO communities.

**Seven Cedars** | [Github](https://github.com/7Cedars) | [Documentation](https://www.google.com/search?q=https://powers-docs.vercel.app)
