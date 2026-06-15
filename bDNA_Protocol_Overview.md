# bDNA Protocol Overview

**Defensive Publication — June 2026**

**The Problem**  
Genomic sequencing and identification today rely on high human and institutional trust. Raw molecular data often needs to be moved or shared, creating privacy risks, sovereignty violations, and future quantum vulnerabilities.

**The Solution**  
bDNA integrates a specialized secure machine (Enclave) with a post-quantum protocol that generates cryptogenomic proof objects directly at the point of sequencing.

The machine samples molecules → the protocol produces a compact, verifiable proof object containing:
- Merkle root of the raw data
- Recursive STARK proofs of analyses performed
- Post-quantum signature (Dilithium)
- Hardware attestation
- Policy-based access control envelope

Raw sequence data never leaves the secure local environment. Only the proof object is shared. Human involvement between sampling and proof generation is minimized or eliminated.

This enables sovereign genomic identification while preserving scientific integrity and post-quantum security.

**Status**  
High-level architecture published for prior art. Detailed implementations are proprietary or in separate repositories (e.g. Lizard-CP-ABE for the access control component).

**License**: CC0 1.0