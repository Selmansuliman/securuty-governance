# Cryptography Policy

## Purpose
Define requirements for secure use and management of cryptographic controls.

## Scope
Data at rest, data in transit, key management, digital signatures.

## Requirements
1. Use approved algorithms (e.g., AES-256 for storage, TLS 1.2+/1.3 for transit).
2. Keys must be generated, stored and retired using HSM or secure KMS.
3. Key rotation policy: at least every 24 months or as risk dictates.

## Exceptions
Any exception requires CISO approval and compensating controls.

## References
ISO: A.8.24 (Use of Cryptography)
