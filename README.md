# RSA Homomorphic Encryption Lab

An educational implementation of RSA encryption demonstrating its multiplicative homomorphic property using Python.

## Overview

This lab demonstrates the basic RSA cryptosystem and shows how operations can be performed on encrypted data.

The experiment focuses on the multiplicative homomorphic property of RSA, where multiplication of ciphertexts corresponds to multiplication of the original plaintexts after decryption.

## Objectives

- Generate RSA public and private keys.
- Encrypt plaintext messages using the RSA public key.
- Decrypt ciphertext using the RSA private key.
- Demonstrate RSA's multiplicative homomorphic property.
- Verify that the decrypted result matches the expected multiplication of plaintext values.

## Technologies

- Python
- Jupyter Notebook
- RSA Cryptography
- Modular Arithmetic

## Implementation

The notebook includes:

1. RSA key generation
2. Public and private key calculation
3. Message encryption
4. Message decryption
5. Homomorphic multiplication demonstration
6. Verification of the results

## Homomorphic Property

For RSA, the multiplicative homomorphic property can be expressed as:

```text
E(m1) × E(m2) mod n = E(m1 × m2 mod n)
