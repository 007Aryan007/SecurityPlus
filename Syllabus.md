# CompTIA Security+ (SY0-701 / Version 7) Exam Syllabus

A comprehensive study tracker and syllabus outline based on the official CompTIA Security+ SY0-701 exam objectives[cite: 1, 2, 3, 4, 5].

---

## Exam Overview

| Detail | Specification |
| :--- | :--- |
| **Exam Code** | SY0-701[cite: 1] |
| **Number of Questions** | Maximum of 90 questions |
| **Type of Questions** | Multiple-choice and Performance-Based Questions (PBQs) |
| **Length of Test** | 90 Minutes |
| **Passing Score** | 750 (on a scale of 100–900) |

---

## Domain Breakdown

| Domain | Exam Weight | Status |
| :--- | :---: | :---: |
| [1.0 General Security Concepts](#domain-10-general-security-concepts-12)[cite: 1] | 12%[cite: 1] | [ ] |
| [2.0 Threats, Vulnerabilities, and Mitigations](#domain-20-threats-vulnerabilities-and-mitigations-22)[cite: 2] | 22%[cite: 2] | [ ] |
| [3.0 Security Architecture](#domain-30-security-architecture-18)[cite: 3] | 18%[cite: 3] | [ ] |
| [4.0 Security Operations](#domain-40-security-operations-28)[cite: 4] | 28%[cite: 4] | [ ] |
| [5.0 Security Program Management and Oversight](#domain-50-security-program-management-and-oversight-20)[cite: 5] | 20%[cite: 5] | [ ] |

---

## Domain 1.0: General Security Concepts (12%)[cite: 1]

- [ ] **1.1 Security Controls & Categories**[cite: 1]
  - [ ] **Control Categories:** Technical, Managerial, Operational, Physical[cite: 1].
  - [ ] **Control Functional Types:** Preventive, Deterrent, Detective, Corrective, Compensating, Directive[cite: 1].
- [ ] **1.2 Fundamental Security Concepts**[cite: 1]
  - [ ] **CIA Triad:** Confidentiality, Integrity, Availability[cite: 1].
  - [ ] **Core Tenets:** Non-repudiation, Authentication, Authorization, and Accounting (AAA)[cite: 1].
  - [ ] **Zero Trust Architecture:** Control plane vs. data plane, implicit trust zones, microsegmentation, policy enforcement points.
  - [ ] **Deception & Disruption Technologies:** Honeypots, honeynets, honeyfiles, honeytokens[cite: 1].
- [ ] **1.3 Change Management Processes**[cite: 1]
  - [ ] Business impact processes, approvals, and Change Advisory Board (CAB)[cite: 1].
  - [ ] Technical implications: rollbacks, sandboxing, version control, downtime planning, standard operating procedures (SOPs)[cite: 1].
- [ ] **1.4 Cryptographic Solutions**[cite: 1]
  - [ ] **Ciphers & Algorithms:** Symmetric (AES, 3DES) vs. Asymmetric (RSA, ECC, Diffie-Hellman).
  - [ ] **Integrity & Authenticity:** SHA-256, SHA-3, HMAC, digital signatures, collision resistance[cite: 1].
  - [ ] **Public Key Infrastructure (PKI):** Certificate Authorities (CAs), CRL vs. OCSP, Certificate Signing Requests (CSR), certificate file formats (`.pem`, `.der`, `.pfx`/`.p12`)[cite: 1].
  - [ ] **Key Concepts:** Obfuscation (steganography, tokenization, data masking), Perfect Forward Secrecy (PFS), blockchain fundamentals[cite: 1].

---

## Domain 2.0: Threats, Vulnerabilities, and Mitigations (22%)[cite: 2]

- [ ] **2.1 Threat Actors and Motivations**[cite: 2]
  - [ ] **Actor Attributes:** Nation-states, Advanced Persistent Threats (APTs), unskilled attackers/script kiddies, hacktivists, insider threats, organized crime, shadow IT[cite: 2].
  - [ ] **Motivations:** Financial gain, data exfiltration, espionage, political/philosophical, competitive advantage, sabotage[cite: 2].
- [ ] **2.2 Threat Vectors and Attack Surfaces**[cite: 2]
  - [ ] **Vectors:** Email/phishing, SMS (smishing), voice call (vishing), supply chain compromise, removable media, unsecure wireless networks[cite: 2].
  - [ ] **Attack Surfaces:** Perimeter, applications, APIs, cloud environments, human/social engineering vectors[cite: 2].
- [ ] **2.3 Vulnerabilities**[cite: 2]
  - [ ] **Application & Web:** Memory leaks, buffer overflows, race conditions, SQL Injection (SQLi), Cross-Site Scripting (XSS), CSRF.
  - [ ] **System & Infrastructure:** Unpatched systems, End-of-Life (EOL)/unsupported products, misconfigurations, default credentials[cite: 2].
  - [ ] **Virtualization & Cloud:** Misconfigured cloud buckets, container breakout, weak API permissions[cite: 2].
- [ ] **2.4 Malicious Activity & Attacks**[cite: 2]
  - [ ] **Malware:** Ransomware, Trojans, worms, spyware, keyloggers, rootkits, fileless malware[cite: 2].
  - [ ] **Network & Resource Attacks:** DoS/DDoS (amplification, reflection), ARP poisoning, DNS hijacking/spoofing, on-path (MitM), rogue APs, evil twins[cite: 2].
  - [ ] **Credential Attacks:** Brute-force, dictionary, rainbow tables, password spraying, credential stuffing[cite: 2].
- [ ] **2.5 Mitigation Techniques**[cite: 2]
  - [ ] Network segmentation (VLANs, DMZ), access control lists (ACLs)[cite: 2].
  - [ ] System hardening, baseline configuration enforcement, air-gapping/isolation, automated patch deployment[cite: 2].

---

## Domain 3.0: Security Architecture (18%)[cite: 3]

- [ ] **3.1 Architecture Models**[cite: 3]
  - [ ] **Environments:** On-premises, cloud (IaaS, PaaS, SaaS; private, public, hybrid, multi-cloud), serverless, edge computing[cite: 3].
  - [ ] **Embedded & Specialized Systems:** Internet of Things (IoT), Industrial Control Systems (ICS/SCADA)[cite: 3].
  - [ ] **Infrastructure as Code (IaC):** Automation templates, configuration drift management, immutable infrastructure[cite: 3].
- [ ] **3.2 Enterprise Infrastructure Principles**[cite: 3]
  - [ ] Infrastructure considerations, defense-in-depth, jump boxes/bastion hosts, forward and reverse proxies[cite: 3].
  - [ ] Secure communication protocols: TLS/HTTPS, SSH, SFTP, IPsec, DNSSEC, SNMPv3[cite: 3].
- [ ] **3.3 Data Protection**[cite: 3]
  - [ ] **Data States:** Data in transit, data at rest, data in use.
  - [ ] **Classifications:** PII, PHI, PCI-DSS, public, internal, confidential, restricted[cite: 3].
  - [ ] **Securing Methods:** Data Loss Prevention (DLP), encryption, tokenization, masking, sanitization/crypto-shredding (NIST 800-88)[cite: 3].
- [ ] **3.4 Resilience and Recovery**[cite: 3]
  - [ ] **High Availability:** Load balancing, clustering, RAID arrays (0, 1, 5, 6, 10), redundant power/generators[cite: 3].
  - [ ] **Site Redundancy:** Hot sites, warm sites, cold sites[cite: 3].
  - [ ] **Backup Strategies:** Full, differential, incremental, snapshots, 3-2-1 backup topology[cite: 3].
  - [ ] **Continuity Planning:** Business Impact Analysis (BIA), Disaster Recovery Plan (DRP), Continuity of Operations (COOP)[cite: 3].

---

## Domain 4.0: Security Operations (28%)[cite: 4]

- [ ] **4.1 Securing Computing Resources**[cite: 4]
  - [ ] Endpoint protection, host-based firewalls, secure baselines, port/service disabling, application allow/deny lists, sandboxing, Mobile Device Management (MDM)[cite: 4].
- [ ] **4.2 Asset & Vulnerability Management**[cite: 4]
  - [ ] Asset discovery, tagging, hardware/software/data lifecycles (procure to decommission)[cite: 4].
  - [ ] Vulnerability identification, CVE tracking, CVSS severity scoring, false positive/negative validation, patch remediation workflows[cite: 4].
- [ ] **4.3 Monitoring, Alerting & Defense Tooling**[cite: 4]
  - [ ] SIEM correlation, log aggregation, alerting rules[cite: 4].
  - [ ] Defense tools: Next-Gen Firewalls (NGFW), IDS/IPS (signature vs. heuristic), Web Application Firewalls (WAF), Network Access Control (NAC), EDR/XDR, DLP[cite: 4].
- [ ] **4.4 Identity and Access Management (IAM)**[cite: 4]
  - [ ] **Authentication & MFA:** Knowledge, possession, inherence factors; passwordless (FIDO2, WebAuthn)[cite: 4].
  - [ ] **Federation & Directory Services:** SAML, OAuth 2.0, OpenID Connect (OIDC), Kerberos, LDAP/LDAPS[cite: 4].
  - [ ] **Access Models & PAM:** Role-Based Access Control (RBAC), Attribute-Based Access Control (ABAC), Privileged Access Management (PAM) vaulting and just-in-time access[cite: 4].
- [ ] **4.5 Automation & Orchestration**[cite: 4]
  - [ ] Security Orchestration, Automation, and Response (SOAR) playbooks, automated response actions, scripting efficiency[cite: 4].
- [ ] **4.6 Incident Response & Digital Forensics**[cite: 4]
  - [ ] **Incident Response Lifecycle:** Preparation, Detection & Analysis, Containment, Eradication, Recovery, Lessons Learned[cite: 4].
  - [ ] **Forensic Investigation:** Order of volatility, chain of custody, legal holds, forensic disk imaging, memory capture[cite: 4].
  - [ ] **Data Sources:** Syslog, Windows Event logs, firewall/proxy logs, DNS queries, authentication records[cite: 4].

---

## Domain 5.0: Security Program Management and Oversight (20%)[cite: 5]

- [ ] **5.1 Security Governance**[cite: 5]
  - [ ] Policy hierarchy: Policies, Standards, Procedures, Guidelines[cite: 5].
  - [ ] Governance frameworks: NIST CSF, ISO/IEC 27001, CIS Controls[cite: 5].
  - [ ] Governance roles: Data Owner, Data Controller, Data Processor, Data Custodian[cite: 5].
- [ ] **5.2 Risk Management**[cite: 5]
  - [ ] Risk assessments: Qualitative (risk matrices) vs. Quantitative calculations ($ALE = SLE \times ARO$)[cite: 5].
  - [ ] Risk treatment options: Accept, Avoid, Mitigate, Transfer (cyber insurance)[cite: 5].
  - [ ] Metrics & Register: Risk registers, Key Risk Indicators (KRIs), RTO, RPO, MTBF, MTTR[cite: 5].
- [ ] **5.3 Third-Party Risk Management**[cite: 5]
  - [ ] Vendor assessments, questionnaires, supply chain risk monitoring[cite: 5].
  - [ ] Contractual mechanisms: SLA, MSA, NDA, MOU, BPA[cite: 5].
- [ ] **5.4 Security Compliance & Privacy**[cite: 5]
  - [ ] Regulatory oversight: GDPR, HIPAA, PCI-DSS, SOC 2 compliance reports[cite: 5].
  - [ ] Privacy principles: Data minimization, data sovereignty, right to be forgotten, Privacy Impact Assessments (PIA)[cite: 5].
- [ ] **5.5 Audits, Assessments & Training**[cite: 5]
  - [ ] Internal vs. external audits, attestations, SOC Type I vs. Type II reporting[cite: 5].
  - [ ] Security testing: Penetration testing (black, grey, white box) vs. vulnerability assessments[cite: 5].
  - [ ] Awareness initiatives: Phishing simulations, anomalous behavior identification, secure reporting culture[cite: 5].