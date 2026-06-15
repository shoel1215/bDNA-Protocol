# bDNA Foundation — Sovereign Genomic Cryptographic Infrastructure

**Public cryptographic infrastructure for scientific integrity.**

bDNA is a protocol that converts raw genomic sequencing data into cryptographically verifiable objects. Raw sequence data remains at the originating institution. Only cryptogenomic proof objects travel.

**Version:** 2.0 (June 2026)  
**License:** Apache 2.0 (protocol & code) / CC0 (publications)  
**Defensive Publication:** Zenodo DOI 10.5281/zenodo.18782639

## Core Principles
- Sovereign control of genomic data
- Post-quantum by design (Dilithium, STARKs, Lizard-CP-ABE)
- Dual-entity structure: bDNA Foundation (non-profit) + Zyan (for-profit hardware)
- Open specification — any accredited lab or nation can implement

## Repository Contents

### `/protocol`
- [Master Booklet v4](protocol/Master_Booklet_v4.md) — Complete project overview
- [Crypto Stack](protocol/Crypto_Stack.md)
- [Cryptogenomic Proof Object](protocol/Proof_Object.md)
- [TSI — Trusted Sequencer Integration](protocol/TSI.md)

### `/hardware`
- [Zyan Enclave Specs](hardware/Enclave_Specs.md) — Sovereign & Compact variants

### `/india`
- [Sovereign India Deployment Model](india/India_Deployment.md)

### `/research`
- [Post-Quantum CP-ABE Open Problem Statement](research/open_problems/Post-Quantum_CP-ABE_Problem_Statement_v1.0.md)
- Lizard-CP-ABE (separate repository)

### `/funding`
- Pre-seed SAFE terms, grant targets (NIH, NSF SaTC)

## Quick Start
```bash
git clone https://github.com/Shoel121516/bDNA-Foundation.git
