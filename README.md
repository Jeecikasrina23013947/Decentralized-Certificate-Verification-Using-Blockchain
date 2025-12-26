# Decentralized Certificate Verification Using Blockchain
The code has been given in my repository
# Abstract

The rapid increase in digital certification has led to a growing risk of forged and tampered credentials. This project presents a decentralized certificate verification system built on the Ethereum blockchain, designed to ensure authenticity, transparency, and immutability of certificates. By storing cryptographic hashes of certificates on the blockchain, the system enables instant and trustless verification without relying on centralized authorities.

# Introduction

Traditional certificate verification systems rely on centralized databases, which are vulnerable to data manipulation, single points of failure, and unauthorized access. Blockchain technology provides a secure alternative by offering decentralization, immutability, and transparency.

This project demonstrates how smart contracts can be used to securely issue and verify certificates, ensuring that once a certificate is issued, it cannot be altered or forged.

# Objectives

To eliminate fake and tampered certificates
To enable secure and decentralized certificate verification
To ensure transparency and data integrity using blockchain
To reduce manual verification time and cost
To provide a trustless verification mechanism

# System Architecture

1.Issuer (University)
Deploys the smart contract and issues certificates.

2.Blockchain (Ethereum)
Stores cryptographic hashes of certificates.

3.Verifier (Employer / Organization)
Verifies certificate authenticity by querying the blockchain.

# Technology Stack

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

# Functional Workflow
**Certificate Issuance**
```
1.The university deploys the smart contract.
2.Certificate details (student name, degree, year) are submitted.
3.A cryptographic hash is generated using Keccak256.
4.The hash is stored permanently on the blockchain.
5.A blockchain event confirms successful issuance.
```
# Certificate Verification
```
1.The verifier enters certificate details.
2.The system regenerates the hash.
3.The blockchain is queried for the hash.
4.Verification result is returned instantly.
```
# Security Considerations

Only the contract owner (university) can issue certificates.
No sensitive personal data is stored on-chain.
Blockchain immutability prevents tampering.
Public verification ensures transparency.

<img width="1457" height="882" alt="image" src="https://github.com/user-attachments/assets/97d0703d-96aa-4aa0-a27c-05df0458ad77" />

![WhatsApp Image 2025-12-26 at 12 41 27 PM](https://github.com/user-attachments/assets/81773494-05b8-4085-9fea-56ceb0183c0c)


<img width="1600" height="731" alt="image" src="https://github.com/user-attachments/assets/61f03882-4951-483e-959c-e446af489c4b" />


<img width="1600" height="751" alt="image" src="https://github.com/user-attachments/assets/551da45b-7fb1-4abe-b174-93a33aab6144" />


# Conclusion

This project demonstrates how blockchain technology can be used to securely issue and verify certificates. By storing certificate hashes on the Ethereum blockchain, the system prevents forgery, ensures data integrity, and enables instant verification without relying on centralized authorities. The solution is efficient, transparent, and suitable for real-world certificate verification applicatio

