# How Group Theory Secures Online Banking and E-Commerce: A Study of RSA Cryptography

## Overview

This project explores the mathematical foundations of **RSA Cryptography** through the lens of **Group Theory**. Rather than treating RSA as a black-box encryption algorithm, the project studies how its correctness and security arise from the structure of finite abelian groups and fundamental results in number theory.

## Objectives

- Understand RSA as exponentiation in the finite abelian group \((\mathbb{Z}_n^*, \times)\)
- Build the mathematical foundations required for RSA, including groups, modular arithmetic, and Euler's Totient Function
- Formally prove RSA correctness using Euler's Theorem and Lagrange's Theorem
- Implement RSA key generation, encryption, and decryption from first principles in Python
- Explore modern cryptographic alternatives and post-quantum challenges

## Mathematical Concepts Covered

- Group Theory
  - Closure
  - Associativity
  - Identity
  - Inverses
  - Finite Abelian Groups
- Modular Arithmetic
- Euler's Totient Function
- Euler's Theorem
- Lagrange's Theorem
- Extended Euclidean Algorithm

## Implementation

A complete RSA implementation was developed from scratch in Python without relying on cryptographic libraries.

### Components Implemented

- RSA Key Generation
- Public and Private Key Computation
- Encryption
- Decryption
- Modular Inverse Calculation using the Extended Euclidean Algorithm

## Security Analysis

The project examines RSA security from a mathematical perspective:

- Why factoring large integers is computationally difficult
- How RSA security depends on the structure of \((\mathbb{Z}_n^*, \times)\)
- Comparison with Elliptic Curve Cryptography (ECC)
- Limitations of RSA in the presence of quantum algorithms such as Shor's Algorithm

## Key Takeaways

- RSA correctness follows naturally from group-theoretic principles rather than being an isolated algorithmic trick.
- Euler's Theorem provides the mathematical foundation for successful decryption.
- Cryptographic security is closely tied to computational hardness assumptions.
- Quantum computing presents significant challenges to classical public-key cryptography.

## Tools Used

- Python
- Extended Euclidean Algorithm
- Modular Arithmetic
- Group Theory
- Number Theory

## Report

A detailed report containing mathematical proofs, worked examples, implementation details, and security analysis is included in this repository.
