# Week 4
Digital Forensics Tasks
# Week 4 – DFIR Incident Response & Forensics Investigation

## Overview
This week focuses on a complete Digital Forensics and Incident Response (DFIR) simulation involving malware infection, command-and-control (C2) communication, evidence collection, memory analysis, disk forensics, malware analysis, containment, and executive reporting.

The investigation follows the NIST Incident Response Lifecycle and MITRE ATT&CK framework to analyze a simulated compromise on endpoint:

- Hostname: WS-FINANCE-01
- IP Address: 192.168.1.55
- Suspicious C2: 203.0.113.88:4444

---

## Objectives

- Perform live incident response investigation
- Collect and preserve forensic evidence
- Analyze memory, disk, and network artifacts
- Identify persistence and exfiltration methods
- Conduct malware triage and IOC extraction
- Build attack timeline and kill-chain diagram
- Produce executive and technical reports

---

## Phases Covered

### Phase 1 — Initial Detection & Scoping
- SIEM alert investigation
- VirusTotal & OTX reputation checks
- Scope assessment
- TheHive case creation

### Phase 2 — Evidence Collection
- Memory acquisition
- Disk imaging
- SHA-256 verification
- Chain of custody documentation

### Phase 3 — Disk Forensics
- Deleted file recovery
- Registry analysis
- Prefetch analysis
- USB activity investigation

### Phase 4 — Memory Forensics
- Volatility 3 analysis
- Process investigation
- C2 connection confirmation
- Shellcode detection

### Phase 5 — Network Analysis
- Wireshark traffic analysis
- Beaconing detection
- Data exfiltration analysis
- Suspicious DNS activity review

### Phase 6 — Malware Analysis
- Static analysis using PEStudio & FLOSS
- Dynamic analysis using ANY.RUN
- IOC extraction
- MITRE ATT&CK mapping
- YARA rule creation

### Phase 7 — Containment & Eradication
- Endpoint isolation
- IOC blocking
- Persistence removal
- Enterprise IOC sweep

### Phase 8 — Timeline Reconstruction
- Unified attack timeline
- Draw.io kill-chain diagram
- MITRE ATT&CK correlation

### Phase 9 — Post-Incident Analysis
- 5 Whys Root Cause Analysis
- Fishbone Diagram
- SOC metrics evaluation
- Security recommendations

### Phase 10 — Reporting
- Executive briefing
- Forensic incident report
- Lessons learned documentation

---

## Tools Used

- Wazuh
- TheHive
- Wireshark
- FTK Imager
- Volatility 3
- PEStudio
- FLOSS
- ANY.RUN
- VirusTotal
- Draw.io
- Google Sheets

---

## Key Learning Outcomes

- DFIR workflow execution
- Evidence preservation techniques
- Malware investigation methodologies
- Threat hunting and IOC analysis
- Attack timeline reconstruction
- Security reporting and documentation
