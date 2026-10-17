# CompTIA Security+ (SY0-701 / Version 7) Exam Syllabus

A comprehensive study tracker and syllabus outline based on the official CompTIA Security+ SY0-701 exam objectives.

---

## Exam Overview

| Detail | Specification |
| :--- | :--- |
| **Exam Code** | SY0-701 |
| **Number of Questions** | Maximum of 90 questions |
| **Type of Questions** | Multiple-choice and Performance-Based Questions (PBQs) |
| **Length of Test** | 90 Minutes |
| **Passing Score** | 750 (on a scale of 100–900) |

---

## Domain Breakdown

| Domain | Exam Weight | Status |
| :--- | :---: | :---: |
| [1.0 General Security Concepts](#domain-10-general-security-concepts-12) | 12% | [ ] |
| [2.0 Threats, Vulnerabilities, and Mitigations](#domain-20-threats-vulnerabilities-and-mitigations-22) | 22% | [ ] |
| [3.0 Security Architecture](#domain-30-security-architecture-18) | 18% | [ ] |
| [4.0 Security Operations](#domain-40-security-operations-28) | 28% | [ ] |
| [5.0 Security Program Management and Oversight](#domain-50-security-program-management-and-oversight-20) | 20% | [ ] |

---

## Domain 1.0: General Security Concepts (12%)

- [ ] **1.1 Security Controls & Categories**
  - [ ] **Control Categories:** Technical, Managerial, Operational, Physical.
  - [ ] **Control Functional Types:** Preventive, Deterrent, Detective, Corrective, Compensating, Directive.
- [ ] **1.2 Fundamental Security Concepts**
  - [ ] **CIA Triad:** Confidentiality, Integrity, Availability.
  - [ ] **Core Tenets:** Non-repudiation, Authentication, Authorization, and Accounting (AAA).
  - [ ] **Zero Trust Architecture:** Control plane vs. data plane, implicit trust zones, microsegmentation, policy enforcement points.
  - [ ] **Deception & Disruption Technologies:** Honeypots, honeynets, honeyfiles, honeytokens.
- [ ] **1.3 Change Management Processes**
  - [ ] Business impact processes, approvals, and Change Advisory Board (CAB).
  - [ ] Technical implications: rollbacks, sandboxing, version control, downtime planning, standard operating procedures (SOPs).
- [ ] **1.4 Cryptographic Solutions**
  - [ ] **Ciphers & Algorithms:** Symmetric (AES, 3DES) vs. Asymmetric (RSA, ECC, Diffie-Hellman).
  - [ ] **Integrity & Authenticity:** SHA-256, SHA-3, HMAC, digital signatures, collision resistance.
  - [ ] **Public Key Infrastructure (PKI):** Certificate Authorities (CAs), CRL vs. OCSP, Certificate Signing Requests (CSR), certificate file formats (`.pem`, `.der`, `.pfx`/`.p12`).
  - [ ] **Key Concepts:** Obfuscation (steganography, tokenization, data masking), Perfect Forward Secrecy (PFS), blockchain fundamentals.

---

## Domain 2.0: Threats, Vulnerabilities, and Mitigations (22%)

- [ ] **2.1 Threat Actors and Motivations**
  - [ ] **Actor Attributes:** Nation-states, Advanced Persistent Threats (APTs), unskilled attackers/script kiddies, hacktivists, insider threats, organized crime, shadow IT.
  - [ ] **Motivations:** Financial gain, data exfiltration, espionage, political/philosophical, competitive advantage, sabotage.
- [ ] **2.2 Threat Vectors and Attack Surfaces**
  - [ ] **Vectors:** Email/phishing, SMS (smishing), voice call (vishing), supply chain compromise, removable media, unsecure wireless networks.
  - [ ] **Attack Surfaces:** Perimeter, applications, APIs, cloud environments, human/social engineering vectors.
- [ ] **2.3 Vulnerabilities**
  - [ ] **Application & Web:** Memory leaks, buffer overflows, race conditions, SQL Injection (SQLi), Cross-Site Scripting (XSS), CSRF.
  - [ ] **System & Infrastructure:** Unpatched systems, End-of-Life (EOL)/unsupported products, misconfigurations, default credentials.
  - [ ] **Virtualization & Cloud:** Misconfigured cloud buckets, container breakout, weak API permissions.
- [ ] **2.4 Malicious Activity & Attacks**
  - [ ] **Malware:** Ransomware, Trojans, worms, spyware, keyloggers, rootkits, fileless malware.
  - [ ] **Network & Resource Attacks:** DoS/DDoS (amplification, reflection), ARP poisoning, DNS hijacking/spoofing, on-path (MitM), rogue APs, evil twins.
  - [ ] **Credential Attacks:** Brute-force, dictionary, rainbow tables, password spraying, credential stuffing.
- [ ] **2.5 Mitigation Techniques**
  - [ ] Network segmentation (VLANs, DMZ), access control lists (ACLs).
  - [ ] System hardening, baseline configuration enforcement, air-gapping/isolation, automated patch deployment.

---

## Domain 3.0: Security Architecture (18%)

- [ ] **3.1 Architecture Models**
  - [ ] **Environments:** On-premises, cloud (IaaS, PaaS, SaaS; private, public, hybrid, multi-cloud), serverless, edge computing.
  - [ ] **Embedded & Specialized Systems:** Internet of Things (IoT), Industrial Control Systems (ICS/SCADA).
  - [ ] **Infrastructure as Code (IaC):** Automation templates, configuration drift management, immutable infrastructure.
- [ ] **3.2 Enterprise Infrastructure Principles**
  - [ ] Infrastructure considerations, defense-in-depth, jump boxes/bastion hosts, forward and reverse proxies.
  - [ ] Secure communication protocols: TLS/HTTPS, SSH, SFTP, IPsec, DNSSEC, SNMPv3.
- [ ] **3.3 Data Protection**
  - [ ] **Data States:** Data in transit, data at rest, data in use.
  - [ ] **Classifications:** PII, PHI, PCI-DSS, public, internal, confidential, restricted.
  - [ ] **Securing Methods:** Data Loss Prevention (DLP), encryption, tokenization, masking, sanitization/crypto-shredding (NIST 800-88).
- [ ] **3.4 Resilience and Recovery**
  - [ ] **High Availability:** Load balancing, clustering, RAID arrays (0, 1, 5, 6, 10), redundant power/generators.
  - [ ] **Site Redundancy:** Hot sites, warm sites, cold sites.
  - [ ] **Backup Strategies:** Full, differential, incremental, snapshots, 3-2-1 backup topology.
  - [ ] **Continuity Planning:** Business Impact Analysis (BIA), Disaster Recovery Plan (DRP), Continuity of Operations (COOP).

---

## Domain 4.0: Security Operations (28%)

- [ ] **4.1 Securing Computing Resources**
  - [ ] Endpoint protection, host-based firewalls, secure baselines, port/service disabling, application allow/deny lists, sandboxing, Mobile Device Management (MDM).
- [ ] **4.2 Asset & Vulnerability Management**
  - [ ] Asset discovery, tagging, hardware/software/data lifecycles (procure to decommission).
  - [ ] Vulnerability identification, CVE tracking, CVSS severity scoring, false positive/negative validation, patch remediation workflows.
- [ ] **4.3 Monitoring, Alerting & Defense Tooling**
  - [ ] SIEM correlation, log aggregation, alerting rules.
  - [ ] Defense tools: Next-Gen Firewalls (NGFW), IDS/IPS (signature vs. heuristic), Web Application Firewalls (WAF), Network Access Control (NAC), EDR/XDR, DLP.
- [ ] **4.4 Identity and Access Management (IAM)**
  - [ ] **Authentication & MFA:** Knowledge, possession, inherence factors; passwordless (FIDO2, WebAuthn).
  - [ ] **Federation & Directory Services:** SAML, OAuth 2.0, OpenID Connect (OIDC), Kerberos, LDAP/LDAPS.
  - [ ] **Access Models & PAM:** Role-Based Access Control (RBAC), Attribute-Based Access Control (ABAC), Privileged Access Management (PAM) vaulting and just-in-time access.
- [ ] **4.5 Automation & Orchestration**
  - [ ] Security Orchestration, Automation, and Response (SOAR) playbooks, automated response actions, scripting efficiency.
- [ ] **4.6 Incident Response & Digital Forensics**
  - [ ] **Incident Response Lifecycle:** Preparation, Detection & Analysis, Containment, Eradication, Recovery, Lessons Learned.
  - [ ] **Forensic Investigation:** Order of volatility, chain of custody, legal holds, forensic disk imaging, memory capture.
  - [ ] **Data Sources:** Syslog, Windows Event logs, firewall/proxy logs, DNS queries, authentication records.

---

## Domain 5.0: Security Program Management and Oversight (20%)

- [ ] **5.1 Security Governance**
  - [ ] Policy hierarchy: Policies, Standards, Procedures, Guidelines.
  - [ ] Governance frameworks: NIST CSF, ISO/IEC 27001, CIS Controls.
  - [ ] Governance roles: Data Owner, Data Controller, Data Processor, Data Custodian.
- [ ] **5.2 Risk Management**
  - [ ] Risk assessments: Qualitative (risk matrices) vs. Quantitative calculations ($ALE = SLE \times ARO$).
  - [ ] Risk treatment options: Accept, Avoid, Mitigate, Transfer (cyber insurance).
  - [ ] Metrics & Register: Risk registers, Key Risk Indicators (KRIs), RTO, RPO, MTBF, MTTR.
- [ ] **5.3 Third-Party Risk Management**
  - [ ] Vendor assessments, questionnaires, supply chain risk monitoring.
  - [ ] Contractual mechanisms: SLA, MSA, NDA, MOU, BPA.
- [ ] **5.4 Security Compliance & Privacy**
  - [ ] Regulatory oversight: GDPR, HIPAA, PCI-DSS, SOC 2 compliance reports.
  - [ ] Privacy principles: Data minimization, data sovereignty, right to be forgotten, Privacy Impact Assessments (PIA).
- [ ] **5.5 Audits, Assessments & Training**
  - [ ] Internal vs. external audits, attestations, SOC Type I vs. Type II reporting.
  - [ ] Security testing: Penetration testing (black, grey, white box) vs. vulnerability assessments.
  - [ ] Awareness initiatives: Phishing simulations, anomalous behavior identification, secure reporting culture.