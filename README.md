# LandLink-DApp
LandLink – Blockchain-Powered Real Estate DApp 

Overview

A decentralized real estate marketplace called LandLink was created to solve the recurring problems in Cameroon's real estate market, including fraud, land ownership conflicts, and ineffective bureaucracy. LandLink offers a transparent, safe, and automated platform for listing, purchasing, and selling real estate by utilizing blockchain technology, distributed systems, and cloud computing. Solidity, Next.js, Hardhat, and IPFS are used in the platform's architecture as a Web3 decentralized application (DApp), which is then deployed on blockchains that support EVMs like Polygon, Ethereum, or BNB Chain.
By using smart contracts to automate ownership transfers and verification, the system reimagines the property management ecosystem while guaranteeing that all data are available to investors, government agencies, and people alike and remain immutable and verifiable. In order to provide a sustainable digital infrastructure for Cameroon's expanding real estate industry, LandLink was designed to be collaborative, scalable, and fault-tolerant.

Problem To Solve

There are several barriers to real estate ownership and development in Cameroon:
1. Manual property Records: The majority of property ownership records are still kept on paper, which makes them vulnerable to manipulation, loss, and physical harm.
2. Corruption and Fraud: Untrustworthy authorities frequently take advantage of centralized systems, which leads to multiple sales and forged ownership documents.
3. Lack of Transparency: There is no single, validated database of land records available to buyers and sellers.
4. Ineffective Bureaucracy: It might take weeks or months to finish property registration and title transfers.
5. Limited Accessibility: It might be challenging for residents in remote locations or overseas to obtain trustworthy real estate information.

LandLink addresses these issues by integrating blockchain and distributed cloud technologies to ensure that every property record is permanently verifiable, tamper-proof, and easily accessible across Cameroon and beyond.

Project Goals:

General Objective

To design and deploy a blockchain-based real estate distributed system that increases transparency, reduces fraud, and streamlines property transactions in Cameroon.

Specific Objectives:

Create smart contracts for escrow management, ownership transfer, and property listing.
• Develop a Next.js frontend that allows users to interface with distributed storage and blockchain technologies.
• Use IPFS integration for decentralized document verification and storage.
For availability, performance, and scalability, make use of cloud infrastructure.
• Make it possible for citizens, agents, surveyors, and government representatives to collaborate with one another.
• Create distributed components that are fault-tolerant to guarantee dependability in the event of system or node failures.


System Overview:

Core Components

Smart Contract Layer: Implements the business logic for listing, verification, escrow, and transfer of property. Built with Solidity and deployed using Hardhat.
Frontend Layer: Built with Next.js and Tailwind CSS for a fast, responsive, and user-friendly experience.
Middleware Layer:  Uses Ethers.js to connect the frontend with blockchain nodes. Handles user transactions and contract calls.
Distributed Storage Layer: IPFS used for storing property documents and media, with corresponding hashes saved on-chain.
Cloud Layer:  Hosts frontend and middleware with redundancy, ensuring high availability and scalability.

Features:

• Blockchain-Based Ownership Verification: All land titles are validated and permanently recorded on the blockchain.
• Property Listing & Purchase: Using linked Web3 wallets, users may list and buy land.
• Automated Escrow Service: Smart contracts safely retain money until both parties meet the terms of the transaction.
• Document Integrity: To guard against forgeries, all land certificates, deeds, and surveys are kept on IPFS.
• Multi-User Collaboration: Designed to assist government verifiers, real estate agents, buyers, and sellers.
• Cloud integration guarantees rapid speed, high system uptime, and worldwide accessibility.

Tech Stack:

Blockchain: Solidity, Hardhat Frontend: Next.js, Tailwind CSS Web3 Libraries: Ethers.js, Web3.js Storage: IPFS (InterPlanetary File System) Blockchain Network: Polygon / Ethereum / BNB Chain Cloud Deployment: AWS / Google Cloud / Render / Vercel Wallet Support: MetaMask and other EVM-compatible wallets

System Architecture:


How It Operates:


1. Registration of Properties
By adding supporting paperwork to the site, property owners register their properties. To guarantee integrity, the document is kept on IPFS and its hash is entered into the blockchain smart contract.
2. Marketplace Listing
Properties are listed on the decentralized marketplace after registration. Through their MetaMask wallet, prospective purchasers may peruse listings, examine information, and start transactions.
3. Procedure for Transactions
In order to guarantee that money is kept safe until the seller certifies the transfer of property, buyers deposit money to a smart contract escrow.
4. Transfer of Ownership
The smart contract automatically updates the on-chain register and transfers ownership after successful verification. The transaction is kept on file forever.

Distributed and Cloud Characteristics:

1. Scalability
•	Horizontal scalability through additional blockchain nodes and cloud server instances.
•	Use of sidechains (Polygon) ensures low transaction fees and fast confirmations.
•	Cloud hosting supports elastic resource allocation to handle varying workloads.
2. Fault Tolerance
•	Data is replicated across multiple blockchain nodes and cloud zones.
•	IPFS ensures distributed storage with redundancy and persistence.
•	System uptime is preserved even if individual components fail.
3. Collaboration Enablement
•	Multiple stakeholders (citizens, government agencies, agents) access the same shared ledger transparently.
•	Smart contracts enforce rules consistently across all participants, ensuring trustless collaboration.
•	Role-based access allows specific functions for each actor without compromising privacy.

Mechanisms of Security
• Blockchain immutability: Prevents ownership history from being changed.
Secure and verifiable transactions are guaranteed via wallet-based authentication.
• Smart Contract Validation: This feature automatically upholds the terms of agreements.
The integrity of submitted documents is ensured via document hashing.
• Managing roles: Differentiating users (buyer, seller, and verifier).

Use Case Scenarios
1. Real estate brokers in the area
Agents list properties transparently via LandLink, and transaction records are publicly verifiable.
2. Buyers from the Diaspora
Through blockchain transactions, Cameroonians living outside may safely buy confirmed land from a distance.


Potential Impact in Cameroon
LandLink provides significant socio-economic benefits:
•	Reduces Corruption: Immutable records prevent data manipulation.
•	Increases Trust: Transparent ownership records enhance public confidence.
•	Boosts Investment: Reliable land registry attracts domestic and foreign investors.
•	Encourages Digitization: Supports Cameroon’s transition to digital governance.
•	Improves Accessibility: Citizens access property data anytime, anywhere.

Future Enhancements
•	AI-Driven Property Valuation
•	Mobile Application Integration (React Native)
•	DeFi-Powered Mortgage Services
•	Decentralized Governance (DAO)
•	Multi-language Support (English, French, Local Dialects)
Contributing:
Contributions are welcome!
1.	Fork the repository.
2.	Create a new branch: git checkout -b feature-branch.
3.	Commit your changes: git commit -m "Add feature".
4.	Push to the branch: git push origin feature-branch.
5.	Submit a pull request.


Contact
Project Lead: SAHA TIOMELA RANDY
Email: saha.tiomela@ictuniversity.edu.cm
GitHub: https://github.com/Randyictu/LandLink-DApp
Institution: ICT UNIVERSITY


Final Note
LandLink demonstrates how distributed systems and blockchain technology can solve long-standing issues in the real estate sector of Cameroon. By combining blockchain transparency, cloud scalability, and collaborative digital governance, this project sets the foundation for a more trustworthy, efficient, and inclusive property market.


