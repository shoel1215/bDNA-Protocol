# bDNA Crypto Stack (High-Level)

**Defensive Publication — June 2026**

bDNA uses a post-quantum cryptographic stack designed for genomic proof objects:

- **Signatures**: Dilithium (FIPS 204)
- **Verifiable Computation**: Recursive STARKs
- **Commitments**: Merkle roots
- **Hardware Attestation**: Secure Enclave / Trusted Execution
- **Access Control**: Post-quantum envelope (Lizard-CP-ABE — see separate repository)

The stack is engineered to eliminate classical pairing-based cryptography (e.g. CP-ABE) that is vulnerable to future quantum computers.

**Purpose**: Public prior art for the post-quantum approach in sovereign genomic identification.

**License**: CC0 1.0