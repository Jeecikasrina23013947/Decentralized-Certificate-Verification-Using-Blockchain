# Decentralized Certificate Verification Using Blockchain
**Abstract**

The rapid increase in digital certification has led to a growing risk of forged and tampered credentials. This project presents a decentralized certificate verification system built on the Ethereum blockchain, designed to ensure authenticity, transparency, and immutability of certificates. By storing cryptographic hashes of certificates on the blockchain, the system enables instant and trustless verification without relying on centralized authorities.

**Introduction**

Traditional certificate verification systems rely on centralized databases, which are vulnerable to data manipulation, single points of failure, and unauthorized access. Blockchain technology provides a secure alternative by offering decentralization, immutability, and transparency.

This project demonstrates how smart contracts can be used to securely issue and verify certificates, ensuring that once a certificate is issued, it cannot be altered or forged.

**Objectives**

To eliminate fake and tampered certificates
To enable secure and decentralized certificate verification
To ensure transparency and data integrity using blockchain
To reduce manual verification time and cost
To provide a trustless verification mechanism

**System Architecture**

1.Issuer (University)
Deploys the smart contract and issues certificates.

2.Blockchain (Ethereum)
Stores cryptographic hashes of certificates.

3.Verifier (Employer / Organization)
Verifies certificate authenticity by querying the blockchain.

**Technology Stack**

Blockchain Platform: Ethereum
Smart Contract Language: Solidity (v0.8.20)
Development Environment: Remix Ethereum IDE

# Smart Contract Overview
**Contract Name**
CertificateVerification

# Core Functionalities
Authorized certificate issuance
Secure hash generation of certificate data
Immutable on-chain storage
Public certificate verification
Event logging for issued certificates

