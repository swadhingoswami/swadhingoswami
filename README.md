# Swadhin Goswami

Systems infrastructure: storage, platform security, and trusted computing.
C++ and Rust, close to the kernel.

---

## Featured Projects

### [CrossPlatformProcessIdentityVerifier][1]

Process identity verification across Windows and Linux using TPM-backed
attestation and secure communication channels.

### [BackupCore][2]

Backup engine with inline deduplication, encrypted snapshots, and
policy-driven retention.

### [LSMStorageEngine][3]

Log-structured merge-tree storage engine with tiered compaction, bloom
filters, and ACID transactions.

### [RuntimeShield][4]

Kernel-level security runtime for process authorization, file integrity
monitoring, and policy enforcement.

### [LinuxTPM][5]

TPM 2.0 command library and tools for Linux — TIS, CRB, session
management, and attestation flows.

---

## Engineering Philosophy

- Clear interfaces over clever implementations
- Correctness over complexity
- Security as a design constraint, not an afterthought
- A system that is boring is predictable. Predictable is operable.

---

## Current Focus

Shipping LinuxTPM toward v1.0. Reworking snapshot metadata in BackupCore
for better incremental performance. The LSM storage engine is a longer-term
project — I return to it when I want to understand a storage concept more
deeply.

---

## Contact

linkedin.com/in/swadhingoswami

[1]: https://github.com/swadhingoswami/CrossPlatformProcessIdentityVerifier
[2]: https://github.com/swadhingoswami/BackupCore
[3]: https://github.com/swadhingoswami/LSMStorageEngine
[4]: https://github.com/swadhingoswami/RuntimeShield
[5]: https://github.com/swadhingoswami/LinuxTPM
