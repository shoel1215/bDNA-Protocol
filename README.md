
# bDNA Protocol — Post-Quantum Sovereign Genomic Data Integrity

**Defensive Publication**

**Problem**  
Current genomic data sharing architectures require either (a) moving raw sequencing data across borders/institutions or (b) relying on classical cryptographic schemes (especially bilinear pairing-based CP-ABE) that are vulnerable to harvest-now-decrypt-later attacks by future cryptographically relevant quantum computers. No NIST-standardized post-quantum solution currently exists for expressive, policy-based access control over long-lived sensitive genomic data while preserving sovereign control of raw data.

**Solution**  
bDNA is a protocol architecture that converts raw genomic sequencing data into compact, cryptographically verifiable **cryptogenomic proof objects** at the point of sequencing. Raw sequence data remains under institutional/sovereign control. Only the proof object travels.

The proof object combines:
- Merkle commitment to the raw data
- Recursive STARK-based verifiable computation of genomic analyses
- Post-quantum digital signatures (Dilithium, FIPS 204)
- Hardware attestation (secure element / Enclave)
- Post-quantum access control envelope (lattice-based CP-ABE successor)

This architecture enables sovereign, post-quantum, policy-enforced sharing of genomic insights without exposing raw data.

**Purpose of this repository**  
This repository serves as public defensive publication of the bDNA protocol concept to establish prior art. It contains only high-level problem statement and solution architecture. No proprietary implementation details, hardware designs, or internal documents are disclosed here.

**Version:** June 2026 (defensive publication)  
**License:** CC0 1.0 (Public Domain Dedication) for this publication

**Contact**  
Shoel Lowy — lowy_s@blockchaindnafoundation.org

---

*This repository is maintained for defensive publication and open scientific prior art only.*