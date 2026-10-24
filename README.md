# Huighlet Eyram Zowonu

**Systems Infrastructure, Cybersecurity & Distributed Systems Engineer**  
Accra, Ghana • [GitHub: @Huighlet](https://github.com/Huighlet) • [Email: huighlet.zowonu@htu.edu.gh](mailto:huighlet.zowonu@htu.edu.gh)

---

## Executive Profile

Specializing in low-latency systems infrastructure, financial core transaction engines, host/network threat detection, and write-optimized distributed storage. Architecting zero-loss financial ledgers, zero-dependency streaming brokers, hardware-near deep packet inspection pipelines, and Model Context Protocol (MCP) decision systems with microsecond benchmarked performance and formal mathematical guarantees.

### Certifications & Academic Credentials
* **Harvard University (CS50 AI):** CS50's Introduction to Artificial Intelligence with Python *(Machine Learning, Deep Neural Networks, Optimization, NLP)*

---

## Flagship Systems Portfolio

### I. Financial Core Infrastructure Suite

| System | Specialization & Architecture | Throughput Benchmark | Tests |
| :--- | :--- | :--- | :--- |
| **[`TitanLedger-Core`](https://github.com/Huighlet/TitanLedger-Core)** | High-throughput immutable double-entry accounting ledger microservice. Implements 32-byte binary Write-Ahead Logging (WAL) with CRC32 frame checksums, group-commit, cryptographic SHA-256 state chain, deadlock-free locking, REST API server (`titanledger serve`), OpenAPI Swagger UI, and Docker deployment. | **10,520 tx/sec** (In-Memory)<br>**8,588 tx/sec** (WAL) | **23/23 Passed** |
| **[`SwitchRail-8583`](https://github.com/Huighlet/SwitchRail-8583)** | Financial switch & protocol engine implementing standard ISO 8583:1987 / ISO 20022 message packaging. Features 64/128-bit bitmap framing, Longest Prefix Match (LPM) BIN routing table, and 0420 Store-and-Forward (SAF) reversals with DE 90 audit trails. | **21,353 pack/sec**<br>**17,833 unpack/sec** | **21/21 Passed** |
| **[`ReliantHook-Engine`](https://github.com/Huighlet/ReliantHook-Engine)** | Zero-loss webhook dispatcher and EOD settlement reconciler. Built with HMAC-SHA256 signatures, replay protection, Full Jitter exponential backoff, per-destination Circuit Breakers, Dead-Letter Queue (DLQ), and a 3-way internal-vs-external financial reconciler. | **81,147 sig/sec**<br>**38,886 dispatch/sec** | **16/16 Passed** |

---

### II. Cybersecurity & Threat Detection Suite

| System | Specialization & Architecture | Throughput Benchmark | Tests |
| :--- | :--- | :--- | :--- |
| **[`AegisFlow-DPI`](https://github.com/Huighlet/AegisFlow-DPI)** | Zero-copy network Deep Packet Inspection (DPI) engine. Features RFC 1035 DNS parser, Shannon entropy DNS tunneling anomaly detector ($H(X) \ge 3.8$ bits/byte), TLS Client Hello parser with JA3/JA4 fingerprinting, and Aho-Corasick multi-pattern signature scanning. | **18,070 packets/sec** | **17/17 Passed** |
| **[`SentinelTrace-EDR`](https://github.com/Huighlet/SentinelTrace-EDR)** | Host Endpoint Detection & Response (EDR) telemetry engine. Tracks process lineage DAGs (PPID tracking), detects behavioral LOLBin anomalies (Office macro spawns, WebShells, Ransomware shadow wipes), executes Sigma-style detection rules, and exports STIX 2.1 CTI bundles. | **26,344 events/sec** | **12/12 Passed** |
| **[`ZeroTrust-Enclave`](https://github.com/Huighlet/ZeroTrust-Enclave)** | Zero-Trust workload attestation control plane. Enforces SPIFFE RFC 3986 workload identity verification via binary SHA-256 digests, issues short-lived HMAC-signed SVID tokens from an Ephemeral CA, and evaluates ABAC microsegmentation policies under strict **Default Deny**. | **75,774 verifications/sec**<br>**197,654 policy evals/sec** | **22/22 Passed** |

---

### III. Data Engineering & Distributed Systems Suite

| System | Specialization & Architecture | Throughput Benchmark | Tests |
| :--- | :--- | :--- | :--- |
| **[`PulseStream-Engine`](https://github.com/Huighlet/PulseStream-Engine)** | In-memory partitioned event streaming broker and append-only commit log. Implements deterministic CRC32 key-based partition routing, monotonic 64-bit offsets, decentralized consumer group coordinators (Range and Round-Robin rebalancing), and Tumbling/Sliding window aggregators. | **506,088 reads/sec**<br>**106,929 appends/sec** | **21/21 Passed** |
| **[`GeoMesh-Stream`](https://github.com/Huighlet/GeoMesh-Stream)** | Real-time geospatial telemetry stream processor. Features Discrete Uniform Spatial Grid Indexing ($\mathcal{O}(1)$ AABB candidate pruning), Haversine spherical distance, Ray-Casting Point-in-Polygon (Jordan curve theorem), and great-circle Dead-Reckoning kinematic extrapolation. | **509,862 spatial queries/sec**<br>**382,666 Haversine/sec** | **16/16 Passed** |
| **[`HyperQuery-LSM`](https://github.com/Huighlet/HyperQuery-LSM)** | Write-optimized Log-Structured Merge-Tree storage engine. Features probabilistic ordered SkipList MemTable, binary WAL with CRC32 crash replay, immutable SSTables with sparse index blocks, Kirsch-Mitzenmacher Bloom filters (100% negative seek bypass), and multi-way leveled compaction. | **156,141 Bloom lookups/sec**<br>**90,959 SkipList inserts/sec** | **16/16 Passed** |

---

## Applied AI & Geospatial Decision Systems

* **[`GeoRisk Platform: Geospatial Risk MCP Server & DSS`](https://github.com/Huighlet/geospatial-risk-mcp-server)**: Model Context Protocol (MCP) server and decision-support dashboard delivering deterministic flood vulnerability calculations, drought indexing, and RFC 7946 GeoJSON bounding-box hazard partitions aligned with the UN Sendai Framework (NASA GPM IMERG, SRTM v3, SMAP L4, MODIS).
* **[`Autonomous SWE Developer Agent`](https://github.com/Huighlet/autonomous-swe-agent)**: Intelligent software engineering agent capable of autonomous codebase exploration, AST symbol traversal, and iterative patch synthesis with fine-tuned open weights.

---

## Core Technical Competencies

* **Systems & Concurrency:** Multi-threading, Reentrant Locking, Ring Buffers, Zero-Copy Slicing, Monotonic Offset Addressing, Deadlock-Free Resource Graph Ordering.
* **Storage & Data Structures:** Log-Structured Merge-Trees (LSM), Sorted String Tables (SSTables), SkipLists, Bloom Filters, Binary Write-Ahead Logs (WAL), Spatial Grid Hash Indexes.
* **Network & Protocols:** ISO 8583:1987 / ISO 20022, RFC 1035 DNS, TLS JA3/JA4 Fingerprinting, RFC 3986 SPIFFE/SPIRE, STIX 2.1 CTI, Ethernet / IPv4 / TCP / UDP Framing.
* **Cryptography & Security:** HMAC-SHA256, Shannon Entropy ($H(X)$), Merkle-Style Chained Hash Ledgers, Attribute-Based Access Control (ABAC), Zero-Trust Workload Attestation.
* **Languages & Tooling:** Python 3.13, C/C++ Interop (ctypes), SQL/PostgreSQL, Bash, PowerShell, Git, Linux, Docker, Pytest.

---

## Contact & Profiles

* **GitHub:** [@Huighlet](https://github.com/Huighlet)
* **Email:** [huighlet.zowonu@htu.edu.gh](mailto:huighlet.zowonu@htu.edu.gh)
