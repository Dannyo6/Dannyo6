# Dhanush V

**Systems Security Engineer & Computer Science Undergraduate**  
*R.N.S. Institute of Technology, Bengaluru (B.E. Computer Science & Engineering — 9.4 CGPA)*  
`Systems Security` • `Endpoint Defense` • `Offensive Security & CTFs` • `Fault-Tolerant Edge Architectures`

---

### Engineering Focus & Philosophy

I engineer defense-in-depth security solutions, real-time endpoint telemetry systems, and resilient decentralized architectures. My engineering approach treats security as an invariant rather than a post-build wrapper—verifying boundary conditions, enforcing strict principle-of-least-privilege primitives, and analyzing attack patterns to construct robust countermeasures.

```text
+--------------------------------------------------------------------------------+
| Systems Security & Threat Defense                                              |
| [ Attack Surface Analysis ] -> [ Threat Modeling ] -> [ Kernel/Host Hardening ] |
|                                                                                |
| Edge Computing & Resilient Systems                                             |
| [ Zero-Trust Comms ]        -> [ Partition Tolerance ] -> [ Telemetry Daemons ] |
+--------------------------------------------------------------------------------+
```

---

### Core Engineering Vectors

- **Systems & Endpoint Defense**: Low-level device interface security, USB bus forensic anomaly monitoring, process isolation, integrity validation, and Linux system call auditing.
- **Offensive Security & CTF Research**: Vulnerability reproduction, SSRF and broken object-level authorization (BOLA) exploitation, heuristic network mapping, binary reverse engineering, and protocol inspection.
- **Resilient Distributed Systems**: Decentralized mesh topology design, edge computing node consensus, and fault-tolerant packet dispatching under partition events.
- **Trustworthy Automation & Pipelines**: Deterministic data parsers, graph schema design, and ingestion engines resilient to hostile or malformed inputs.

---

### Flagship Systems Architecture

#### 1. [Shield.USB](https://github.com/Dannyo6/shield-usb)
*Air-Gapped Endpoint Defense & Hardware Interface Monitoring Daemon*
- **Problem**: Hostile physical device injection (BadUSB, malicious HID emulators, and exfiltration via unauthorized mass storage) bypasses network boundary controls.
- **Solution**: Developed a host-level monitoring service that intercepts insertion events, parses vendor/product device signatures, audits file-system change rates, and flags mass I/O anomalies in real time.
- **Stack**: Python, Linux Subsystems / Win32 API, Endpoint Telemetry.

#### 2. [SentinelScan](https://github.com/Dannyo6/sentinel-scan)
*Asynchronous Reconnaissance Engine & Surface Threat Analyzer*
- **Problem**: Monolithic port scanners either overwhelm low-resource targets or introduce latency when aggregating protocol banner telemetry.
- **Solution**: Engineered an asynchronous scanning engine using non-blocking sockets to perform rapid port enumeration, service signature extraction, and CVE surface mapping with low overhead.
- **Stack**: Python `asyncio`, Socket Programming, Threat Intelligence Feeds.

#### 3. [MeshAid](https://github.com/Dannyo6/meshaid)
*Decentralized Edge Relay Network for Emergency Telemetry*
- **Problem**: Complete failure of terrestrial cellular/broadband uplinks during disaster events isolates critical field telemetry.
- **Solution**: Designed a store-and-forward edge routing layer capable of operating on battery-backed decentralized nodes with dynamic peer discovery and payload verification.
- **Stack**: Distributed Systems Protocols, Edge Microcontrollers, Embedded C/C++, Network Reliability.

#### 4. [RNSIT Alumni Intelligence](https://github.com/Dannyo6/rnsit-alumni-intelligence)
*Structured Entity Ingestion & Knowledge Graph Pipeline*
- **Problem**: Unstructured academic and professional profile data suffers from entity ambiguity and schema drift over time.
- **Solution**: Implemented an automated parsing and data normalization engine mapping institutional graph relationships, career progression vectors, and network nodes with verification layers.
- **Stack**: Python, Data Modeling, Graph Relational Databases, Automated Extraction.

---

### Offensive Security & Practical CTF Methodology

Offensive testing directly informs defensive engineering. My security methodology emphasizes real attack mechanics:

```text
+-------------------+      +---------------------+      +----------------------+
|  Recon & Mapping  | ---> | Exploitation Vector | ---> | Defensive Hardening  |
| ASN/Port/Protocol |      | SSRF / Injections   |      | Least Privilege &    |
| Surface Tracing   |      | IDOR / Auth Bypass  |      | Strict Input Typing  |
+-------------------+      +---------------------+      +----------------------+
```

- **Protocol & Network Enumeration**: Dissecting Layer 4/7 protocols, analyzing packet captures (Wireshark/tshark), and identifying unauthenticated services or legacy protocol fallbacks.
- **Web Application Vulnerability Analysis**: Identifying logic vulnerabilities, Server-Side Request Forgery (SSRF), race conditions in financial/session logic, and injection boundaries.
- **Binary & System Hardening**: Investigating stack canaries, ASLR/DEP configurations, and ELF binary structures to comprehend memory safety pitfalls and apply mitigation patterns in written software.

---

### Technical Capabilities Matrix

| Domain | Technologies & Tooling |
| :--- | :--- |
| **Languages** | Python, C/C++, SQL, Bash, Go *(Familiarity)* |
| **Security & Auditing** | Wireshark, Nmap, Burp Suite, Sysinternals, Ghidra, Linux Auditing (`auditd`), GDB |
| **Systems & Platforms** | Linux (Debian, Arch, Alpine), Windows Internals, POSIX API, Docker, Edge MCUs |
| **Networking & Protocols** | TCP/IP, UDP, DNS, TLS/SSL, HTTP/2, Socket Programming, Distributed Mesh Relays |
| **Architecture & Core** | Concurrency, Memory Safety Primitives, System Call Tracing, Threat Modeling |

---

### Verified Verification & Academic Record

- **Degree**: Bachelor of Engineering in Computer Science & Engineering
- **Institution**: R.N.S. Institute of Technology (RNSIT), Bengaluru
- **Academic Performance**: **9.4 CGPA**
- **Contact**: Reachable via [GitHub Issues](https://github.com/Dannyo6/Dannyo6/issues) or professional profiles linked on this page.
