Hi there! I am Akhil Bandarupalli, a postdoctoral associate at Duke University, hosted by Prof. Michael Reiter. I received my Ph.D. in Computer Science at Purdue University where I was advised by Prof. Aniket Kate and Prof. Saurabh Bagchi. 

### Research Interests
I design fault-tolerant distributed computing protocols for privacy-preserving computation, and resource-constrained Cyber-Physical Systems. My research combines novel distributed computing techniques with cryptography to build protocols with provable security and efficiency. My current research focuses on computationally efficient distributed protocols for Multi-Party Computation, Asynchronous Random Beacons, and Convex Byzantine Agreement. I practically implement my research and aim to produce quality software artifacts that can be employed in real-world applications.

### Artifacts
I produced multiple software artifacts as part of my research. Each artifact is set up in a separate Github repository. 

1. The `velox` repository implements Velox, an asynchronous Multi-Party Computation protocol published at ACM CCS'25, in Rust. This codebase orchestrates multiple smaller distributed protocols to build MPC, often deemed to be the holy grail of cryptography, in real-world networks. This codebase executes reliably in systems comprising hundreds of parties with a high degree of concurrency and parallelism. 

2. The `secure-distributed-computing-protocols` repository contains implementations of multiple distributed protocols, which act as building blocks of fault-tolerant distributed systems, in Rust. Any entity who wants to implement complex asynchronous distributed systems can use the implementations in this repo in a plug-and-play manner and do not have to implement every sub-primitive from scratch.

3. The `acss-rs` repository implements highly performant Verifiable Secret Sharing (VSS) protocols that can facilitate secret sharing of millions of secrets among hundreds of parties. These protocols utilize computationally efficient (or lightweight) cryptographic primitives like symmetric-key encryption and cryptographic Hash functions for performance efficiency. 

4. The `hashrand-rs` repository implements HashRand, a computationally efficient asynchronous random beacon protocol (CCS'24). This repository also contains an implementation of the Dfinity-DVRF beacon protocol based on threshold BLS signatures. These protocols have been implemented in Rust. This artifact is also available on Zenodo. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11176836.svg)](https://doi.org/10.5281/zenodo.11176836)

5. The `delphi-rs` repository implements Delphi, a computationally efficient asynchronous convex agreement protocol (DSN'24). This repository also contains an implementation of the FIN Asynchronous Common Subset (ACS) protocol, and Abraham et al.'s Approximate Agreement protocol. These protocols have been implemented in Rust. This artifact is also available on Zenodo. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11061584.svg)](https://doi.org/10.5281/zenodo.11061584)

6. The `pqsmr-rs` repository implements PQ-Tusk (CCS'24), a Post-Quantum secure asynchronous State Machine Replication (SMR) protocol. This protocol uses Dilithium signatures for certificate generation. These protocols have been implemented in Rust. This artifact is also available on Zenodo.  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11176836.svg)](https://doi.org/10.5281/zenodo.11176836)

7. The `sensorbft-rs` repository implements SensorBFT (ICDCS'24), an efficient asynchronous approximate agreement protocol for target localization. This protocol has been implemented in Rust.

8. The `E2C-BLE` repository implements EESMR, an energy-efficient synchronous State Machine Replication (SMR) protocol. This artifact has been implemented in C++. This artifact uses libraries from `mbedos`, a lightweight OS for low-power embedded devices. 

<!--
**akhilsb/akhilsb** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
