# Swadhin Goswami

Staff Software Engineer focused on systems programming, platform security, storage systems, and infrastructure software.

I enjoy building software close to the operating system where correctness, performance, and reliability matter. My primary interests include C++, Rust, Linux internals, trusted computing (TPM 2.0), storage engines, backup systems, and cross-platform infrastructure.

This GitHub serves as my engineering portfolio, where I document ideas, explore system design concepts, and build production-quality open-source projects.

---

## Core Areas

- Systems Programming
- Platform Security
- Linux Internals
- Storage Engines
- Backup & Recovery
- Trusted Platform Module (TPM 2.0)
- Cryptography
- Cross-Platform Development
- Performance Engineering

---

## 🚀 Systems & Infrastructure Projects

I build systems software across **GPU runtimes, storage, security, Linux kernel, and AI/data infrastructure**, with a focus on performance, reliability, and low-level system design.

### 🔥 GPUFlux

<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/31f87318-70e2-4c6c-a64e-72b48c88a89b" />

**Adaptive runtime for GPU data movement, recomputation, and remote execution**

GPUFlux explores runtime decisions for GPU workloads under changing GPU memory, CPU, PCIe, storage, and network conditions. It decides whether to **move, recompute, prefetch, cache, or remotely fetch** data using predicted completion time, uncertainty, resource contention, and dependency deadlines.

🔗 [GPUFlux](https://github.com/swadhingoswami/GPUFlux)

---

### 💾 HELIX

<img width="1408" height="768" alt="Gemini_Generated_Image_p3vi8fp3vi8fp3vi" src="https://github.com/user-attachments/assets/e7295289-da93-4905-b361-b223f6f9cfae" />

**Block-level, filesystem-independent backup engine**

HELIX approaches backup at the **storage block layer** rather than relying on filesystem-level file enumeration. It tracks changed blocks and stores only the data required for incremental backup and recovery.

**Focus:** Raw block devices · Incremental backup · Change tracking · Deduplication · Recovery · Storage systems

🔗 [helix-backup](https://github.com/swadhingoswami/helix-backup)

---

### 🛡️ RuntimeShield

<img width="1408" height="768" alt="Gemini_Generated_Image_18d5ex18d5ex18d5 (1)" src="https://github.com/user-attachments/assets/651e866c-042f-4d10-9598-47aa0ea8dc6b" />

**Cross-platform runtime application protection framework**

RuntimeShield explores runtime trust and integrity verification for native applications across **Linux, Windows, and macOS**.

**Focus:** Executable integrity · Process identity · Module verification · Runtime tamper detection · Cryptographic verification · Security policies · Audit logging

🔗 [RuntimeShield](https://github.com/swadhingoswami/RuntimeShield)

---

### 🧠 TuckDB

<img width="1376" height="768" alt="image" src="https://github.com/user-attachments/assets/beb79905-6d75-4bff-b387-576d3c92cacd" />

**Incremental vector data engine for evolving AI workloads**

TuckDB explores an incremental architecture for AI and vector workloads where small data changes should not require large-scale reprocessing. The system focuses on identifying what actually changed and updating only the affected data.

**Focus:** Incremental processing · Vector/RAG lifecycle · Change-aware updates · Hybrid SQL + NoSQL · Storage-oriented processing

🔗 [TuckDB](https://github.com/swadhingoswami/tuckdb)

---

### 🐧 eBPF FileGuard

<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/6fac4d40-f448-4e48-912a-94fb3a68b5c2" />

**Kernel-assisted runtime file access control**

eBPF FileGuard explores using **eBPF LSM** to enforce runtime file-access policies directly at the Linux kernel layer using a default-deny security model.

**Focus:** eBPF LSM · Kernel security · File access control · Process-aware policies · Allow-list authorization · Runtime protection

🔗 [eBPF FileGuard](https://github.com/swadhingoswami/ebpf-fileguard)


## Featured Projects

### CrossPlatformProcessIdentityVerifier
https://github.com/swadhingoswami/CrossPlatformProcessIdentityVerifier

A cross-platform framework exploring process identity verification using trusted computing, cryptographic verification, and secure communication between applications.

**Focus**

- Process Identity
- TPM-backed Trust
- Secure IPC
- Platform Security
- Windows, Linux and macOS

---

### LSMStorageEngine
https://github.com/swadhingoswami/LSMStorageEngine
An educational implementation of a Log-Structured Merge Tree storage engine to better understand modern database internals.

Current areas of exploration include:

- MemTable
- Write Ahead Log
- SSTables
- Bloom Filters
- Compaction
- Recovery

---

## Technology Stack

### Languages

- C++
- C#
- Rust
- Python

### Platforms

- Linux
- Windows
- macOS

### Technologies

- TPM 2.0
- OpenSSL
- SQLite
- CMake
- Git
- Docker
- GitHub Actions

---

## Engineering Philosophy

I enjoy understanding how systems work beneath the abstraction layers.

My projects emphasize:

- Clear architecture
- Well-defined interfaces
- Correctness over complexity
- Security by design
- Maintainable code
- Thorough documentation

---

## Current Focus

Currently investing time in building production-quality open-source projects around:

- Platform Security
- Storage Systems
- Backup Infrastructure
- Trusted Computing
- Cross-Platform System Software

---

## Engineering Philosophy

- Clear interfaces over clever implementations
- Correctness over complexity
- Security as a design constraint, not an afterthought
- A system that is boring is predictable. Predictable is operable.

---

## Connect

- 💼 LinkedIn: https://linkedin.com/in/swadhingoswami
- 📧 Email: gsmswadhin@gmail.com

I'm always interested in discussions around systems programming, storage, platform security, and open-source infrastructure.
