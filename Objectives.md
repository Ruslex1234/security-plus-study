# CompTIA Security+ SY0-701 Study Guide

**Exam Version:** 5.0  
**Exam Code:** SY0-701  
**Last Updated:** December 2024

## Exam Overview

- **Questions:** Maximum of 90
- **Question Types:** Multiple-choice and performance-based
- **Duration:** 90 minutes
- **Passing Score:** 750 (on a scale of 100-900)
- **Recommended Experience:** Minimum 2 years IT administration with security focus

## Domain Breakdown

| Domain | Weight | Questions (approx) |
|--------|--------|-------------------|
| 1.0 General Security Concepts | 12% | ~11 questions |
| 2.0 Threats, Vulnerabilities, and Mitigations | 22% | ~20 questions |
| 3.0 Security Architecture | 18% | ~16 questions |
| 4.0 Security Operations | 28% | ~25 questions |
| 5.0 Security Program Management and Oversight | 20% | ~18 questions |

---

## Domain 1.0: General Security Concepts (12%)

### 1.1 Compare and contrast various types of security controls

**Categories:**
- [ ] Technical
- [ ] Managerial
- [ ] Operational
- [ ] Physical

**Control Types:**
- [ ] Preventive
- [ ] Deterrent
- [ ] Detective
- [ ] Corrective
- [ ] Compensating
- [ ] Directive

### 1.2 Summarize fundamental security concepts

**Core Principles:**
- [ ] Confidentiality, Integrity, and Availability (CIA)
- [ ] Non-repudiation

**AAA Framework:**
- [ ] Authentication, Authorization, and Accounting (AAA)
  - [ ] Authenticating people
  - [ ] Authenticating systems
  - [ ] Authorization models

**Security Frameworks:**
- [ ] Gap analysis
- [ ] Zero Trust
  - [ ] Control Plane
    - [ ] Adaptive identity
    - [ ] Threat scope reduction
    - [ ] Policy-driven access control
    - [ ] Policy Administrator
    - [ ] Policy Engine
  - [ ] Data Plane
    - [ ] Implicit trust zones
    - [ ] Subject/System
    - [ ] Policy Enforcement Point

**Physical Security:**
- [ ] Bollards
- [ ] Access control vestibule
- [ ] Fencing
- [ ] Video surveillance
- [ ] Security guard
- [ ] Access badge
- [ ] Lighting
- [ ] Sensors
  - [ ] Infrared
  - [ ] Pressure
  - [ ] Microwave
  - [ ] Ultrasonic

**Deception and Disruption Technology:**
- [ ] Honeypot
- [ ] Honeynet
- [ ] Honeyfile
- [ ] Honeytoken

### 1.3 Explain the importance of change management processes and the impact to security

**Business Processes Impacting Security:**
- [ ] Approval process
- [ ] Ownership
- [ ] Stakeholders
- [ ] Impact analysis
- [ ] Test results
- [ ] Backout plan
- [ ] Maintenance window
- [ ] Standard operating procedure

**Technical Implications:**
- [ ] Allow lists/deny lists
- [ ] Restricted activities
- [ ] Downtime
- [ ] Service restart
- [ ] Application restart
- [ ] Legacy applications
- [ ] Dependencies

**Documentation:**
- [ ] Updating diagrams
- [ ] Updating policies/procedures
- [ ] Version control

### 1.4 Explain the importance of using appropriate cryptographic solutions

**Public Key Infrastructure (PKI):**
- [ ] Public key
- [ ] Private key
- [ ] Key escrow

**Encryption:**
- [ ] Level
  - [ ] Full-disk
  - [ ] Partition
  - [ ] File
  - [ ] Volume
  - [ ] Database
  - [ ] Record
- [ ] Transport/communication
- [ ] Asymmetric
- [ ] Symmetric
- [ ] Key exchange
- [ ] Algorithms
- [ ] Key length

**Tools:**
- [ ] Trusted Platform Module (TPM)
- [ ] Hardware security module (HSM)
- [ ] Key management system
- [ ] Secure enclave

**Obfuscation:**
- [ ] Steganography
- [ ] Tokenization
- [ ] Data masking

**Other Concepts:**
- [ ] Hashing
- [ ] Salting
- [ ] Digital signatures
- [ ] Key stretching
- [ ] Blockchain
- [ ] Open public ledger

**Certificates:**
- [ ] Certificate authorities
- [ ] Certificate revocation lists (CRLs)
- [ ] Online Certificate Status Protocol (OCSP)
- [ ] Self-signed
- [ ] Third-party
- [ ] Root of trust
- [ ] Certificate signing request (CSR) generation
- [ ] Wildcard

---

## Domain 2.0: Threats, Vulnerabilities, and Mitigations (22%)

### 2.1 Compare and contrast common threat actors and motivations

**Threat Actors:**
- [ ] Nation-state
- [ ] Unskilled attacker
- [ ] Hacktivist
- [ ] Insider threat
- [ ] Organized crime
- [ ] Shadow IT

**Attributes of Actors:**
- [ ] Internal/external
- [ ] Resources/funding
- [ ] Level of sophistication/capability

**Motivations:**
- [ ] Data exfiltration
- [ ] Espionage
- [ ] Service disruption
- [ ] Blackmail
- [ ] Financial gain
- [ ] Philosophical/political beliefs
- [ ] Ethical
- [ ] Revenge
- [ ] Disruption/chaos
- [ ] War

### 2.2 Explain common threat vectors and attack surfaces

**Message-Based:**
- [ ] Email
- [ ] Short Message Service (SMS)
- [ ] Instant messaging (IM)

**Other Vectors:**
- [ ] Image-based
- [ ] File-based
- [ ] Voice call
- [ ] Removable device

**Vulnerable Software:**
- [ ] Client-based vs. agentless

**Systems and Networks:**
- [ ] Unsupported systems and applications
- [ ] Unsecure networks
  - [ ] Wireless
  - [ ] Wired
  - [ ] Bluetooth
- [ ] Open service ports
- [ ] Default credentials

**Supply Chain:**
- [ ] Managed service providers (MSPs)
- [ ] Vendors
- [ ] Suppliers

**Human Vectors/Social Engineering:**
- [ ] Phishing
- [ ] Vishing
- [ ] Smishing
- [ ] Misinformation/disinformation
- [ ] Impersonation
- [ ] Business email compromise
- [ ] Pretexting
- [ ] Watering hole
- [ ] Brand impersonation
- [ ] Typosquatting

### 2.3 Explain various types of vulnerabilities

**Application Vulnerabilities:**
- [ ] Memory injection
- [ ] Buffer overflow
- [ ] Race conditions
  - [ ] Time-of-check (TOC)
  - [ ] Time-of-use (TOU)
- [ ] Malicious update

**Operating System (OS)-based:**
- [ ] OS vulnerabilities

**Web-based:**
- [ ] Structured Query Language injection (SQLi)
- [ ] Cross-site scripting (XSS)

**Hardware:**
- [ ] Firmware
- [ ] End-of-life
- [ ] Legacy

**Virtualization:**
- [ ] Virtual machine (VM) escape
- [ ] Resource reuse

**Other Vulnerabilities:**
- [ ] Cloud-specific
- [ ] Supply chain
  - [ ] Service provider
  - [ ] Hardware provider
  - [ ] Software provider
- [ ] Cryptographic
- [ ] Misconfiguration
- [ ] Mobile device
  - [ ] Side loading
  - [ ] Jailbreaking
- [ ] Zero-day

### 2.4 Given a scenario, analyze indicators of malicious activity

**Malware Attacks:**
- [ ] Ransomware
- [ ] Trojan
- [ ] Worm
- [ ] Spyware
- [ ] Bloatware
- [ ] Virus
- [ ] Keylogger
- [ ] Logic bomb
- [ ] Rootkit

**Physical Attacks:**
- [ ] Brute force
- [ ] Radio frequency identification (RFID) cloning
- [ ] Environmental

**Network Attacks:**
- [ ] Distributed denial-of-service (DDoS)
  - [ ] Amplified
  - [ ] Reflected
- [ ] Domain Name System (DNS) attacks
- [ ] Wireless
- [ ] On-path
- [ ] Credential replay
- [ ] Malicious code

**Application Attacks:**
- [ ] Injection
- [ ] Buffer overflow
- [ ] Replay
- [ ] Privilege escalation
- [ ] Forgery
- [ ] Directory traversal

**Cryptographic Attacks:**
- [ ] Downgrade
- [ ] Collision
- [ ] Birthday

**Password Attacks:**
- [ ] Spraying
- [ ] Brute force

**Indicators:**
- [ ] Account lockout
- [ ] Concurrent session usage
- [ ] Blocked content
- [ ] Impossible travel
- [ ] Resource consumption
- [ ] Resource inaccessibility
- [ ] Out-of-cycle logging
- [ ] Published/documented
- [ ] Missing logs

### 2.5 Explain the purpose of mitigation techniques used to secure the enterprise

**Mitigation Techniques:**
- [ ] Segmentation
- [ ] Access control
  - [ ] Access control list (ACL)
  - [ ] Permissions
- [ ] Application allow list
- [ ] Isolation
- [ ] Patching
- [ ] Encryption
- [ ] Monitoring
- [ ] Least privilege
- [ ] Configuration enforcement
- [ ] Decommissioning

**Hardening Techniques:**
- [ ] Encryption
- [ ] Installation of endpoint protection
- [ ] Host-based firewall
- [ ] Host-based intrusion prevention system (HIPS)
- [ ] Disabling ports/protocols
- [ ] Default password changes
- [ ] Removal of unnecessary software

---

## Domain 3.0: Security Architecture (18%)

### 3.1 Compare and contrast security implications of different architecture models

**Architecture and Infrastructure Concepts:**
- [ ] Cloud
  - [ ] Responsibility matrix
  - [ ] Hybrid considerations
  - [ ] Third-party vendors
- [ ] Infrastructure as code (IaC)
- [ ] Serverless
- [ ] Microservices
- [ ] Network infrastructure
  - [ ] Physical isolation (Air-gapped)
  - [ ] Logical segmentation
  - [ ] Software-defined networking (SDN)
- [ ] On-premises
- [ ] Centralized vs. decentralized
- [ ] Containerization
- [ ] Virtualization
- [ ] IoT
- [ ] Industrial control systems (ICS)/SCADA
- [ ] Real-time operating system (RTOS)
- [ ] Embedded systems
- [ ] High availability

**Considerations:**
- [ ] Availability
- [ ] Resilience
- [ ] Cost
- [ ] Responsiveness
- [ ] Scalability
- [ ] Ease of deployment
- [ ] Risk transference
- [ ] Ease of recovery
- [ ] Patch availability
- [ ] Inability to patch
- [ ] Power
- [ ] Compute

### 3.2 Given a scenario, apply security principles to secure enterprise infrastructure

**Infrastructure Considerations:**
- [ ] Device placement
- [ ] Security zones
- [ ] Attack surface
- [ ] Connectivity
- [ ] Failure modes
  - [ ] Fail-open
  - [ ] Fail-closed
- [ ] Device attribute
  - [ ] Active vs. passive
  - [ ] Inline vs. tap/monitor

**Network Appliances:**
- [ ] Jump server
- [ ] Proxy server
- [ ] Intrusion prevention system (IPS)/intrusion detection system (IDS)
- [ ] Load balancer
- [ ] Sensors

**Port Security:**
- [ ] 802.1X
- [ ] Extensible Authentication Protocol (EAP)

**Firewall Types:**
- [ ] Web application firewall (WAF)
- [ ] Unified threat management (UTM)
- [ ] Next-generation firewall (NGFW)
- [ ] Layer 4/Layer 7

**Secure Communication/Access:**
- [ ] Virtual private network (VPN)
- [ ] Remote access
- [ ] Tunneling
  - [ ] Transport Layer Security (TLS)
  - [ ] Internet protocol security (IPSec)
- [ ] Software-defined wide area network (SD-WAN)
- [ ] Secure access service edge (SASE)

**Selection of Effective Controls:**
- [ ] Control selection methodology

### 3.3 Compare and contrast concepts and strategies to protect data

**Data Types:**
- [ ] Regulated
- [ ] Trade secret
- [ ] Intellectual property
- [ ] Legal information
- [ ] Financial information
- [ ] Human- and non-human-readable

**Data Classifications:**
- [ ] Sensitive
- [ ] Confidential
- [ ] Public
- [ ] Restricted
- [ ] Private
- [ ] Critical

**General Data Considerations:**
- [ ] Data states
  - [ ] Data at rest
  - [ ] Data in transit
  - [ ] Data in use
- [ ] Data sovereignty
- [ ] Geolocation

**Methods to Secure Data:**
- [ ] Geographic restrictions
- [ ] Encryption
- [ ] Hashing
- [ ] Masking
- [ ] Tokenization
- [ ] Obfuscation
- [ ] Segmentation
- [ ] Permission restrictions

### 3.4 Explain the importance of resilience and recovery in security architecture

**High Availability:**
- [ ] Load balancing vs. clustering

**Site Considerations:**
- [ ] Hot
- [ ] Cold
- [ ] Warm
- [ ] Geographic dispersion

**Business Continuity:**
- [ ] Platform diversity
- [ ] Multi-cloud systems
- [ ] Continuity of operations

**Capacity Planning:**
- [ ] People
- [ ] Technology
- [ ] Infrastructure

**Testing:**
- [ ] Tabletop exercises
- [ ] Fail over
- [ ] Simulation
- [ ] Parallel processing

**Backups:**
- [ ] Onsite/offsite
- [ ] Frequency
- [ ] Encryption
- [ ] Snapshots
- [ ] Recovery
- [ ] Replication
- [ ] Journaling

**Power:**
- [ ] Generators
- [ ] Uninterruptible power supply (UPS)

---

## Domain 4.0: Security Operations (28%)

### 4.1 Given a scenario, apply common security techniques to computing resources

**Secure Baselines:**
- [ ] Establish
- [ ] Deploy
- [ ] Maintain

**Hardening Targets:**
- [ ] Mobile devices
- [ ] Workstations
- [ ] Switches
- [ ] Routers
- [ ] Cloud infrastructure
- [ ] Servers
- [ ] ICS/SCADA
- [ ] Embedded systems
- [ ] RTOS
- [ ] IoT devices

**Wireless Devices:**
- [ ] Installation considerations
  - [ ] Site surveys
  - [ ] Heat maps

**Mobile Solutions:**
- [ ] Mobile device management (MDM)
- [ ] Deployment models
  - [ ] Bring your own device (BYOD)
  - [ ] Corporate-owned, personally enabled (COPE)
  - [ ] Choose your own device (CYOD)
- [ ] Connection methods
  - [ ] Cellular
  - [ ] Wi-Fi
  - [ ] Bluetooth

**Wireless Security Settings:**
- [ ] Wi-Fi Protected Access 3 (WPA3)
- [ ] AAA/Remote Authentication Dial-In User Service (RADIUS)
- [ ] Cryptographic protocols
- [ ] Authentication protocols

**Application Security:**
- [ ] Input validation
- [ ] Secure cookies
- [ ] Static code analysis
- [ ] Code signing
- [ ] Sandboxing
- [ ] Monitoring

### 4.2 Explain the security implications of proper hardware, software, and data asset management

**Asset Management Lifecycle:**
- [ ] Acquisition/procurement process
- [ ] Assignment/accounting
  - [ ] Ownership
  - [ ] Classification
- [ ] Monitoring/asset tracking
  - [ ] Inventory
  - [ ] Enumeration
- [ ] Disposal/decommissioning
  - [ ] Sanitization
  - [ ] Destruction
  - [ ] Certification
  - [ ] Data retention

### 4.3 Explain various activities associated with vulnerability management

**Identification Methods:**
- [ ] Vulnerability scan
- [ ] Application security
  - [ ] Static analysis
  - [ ] Dynamic analysis
  - [ ] Package monitoring
- [ ] Threat feed
  - [ ] Open-source intelligence (OSINT)
  - [ ] Proprietary/third-party
  - [ ] Information-sharing organization
  - [ ] Dark web
- [ ] Penetration testing
- [ ] Responsible disclosure program
  - [ ] Bug bounty program
- [ ] System/process audit

**Analysis:**
- [ ] Confirmation
  - [ ] False positive
  - [ ] False negative
- [ ] Prioritize
- [ ] Common Vulnerability Scoring System (CVSS)
- [ ] Common Vulnerability Enumeration (CVE)
- [ ] Vulnerability classification
- [ ] Exposure factor
- [ ] Environmental variables
- [ ] Industry/organizational impact
- [ ] Risk tolerance

**Vulnerability Response and Remediation:**
- [ ] Patching
- [ ] Insurance
- [ ] Segmentation
- [ ] Compensating controls
- [ ] Exceptions and exemptions

**Validation of Remediation:**
- [ ] Rescanning
- [ ] Audit
- [ ] Verification
- [ ] Reporting

### 4.4 Explain security alerting and monitoring concepts and tools

**Monitoring Computing Resources:**
- [ ] Systems
- [ ] Applications
- [ ] Infrastructure

**Activities:**
- [ ] Log aggregation
- [ ] Alerting
- [ ] Scanning
- [ ] Reporting
- [ ] Archiving
- [ ] Alert response and remediation/validation
  - [ ] Quarantine
  - [ ] Alert tuning

**Tools:**
- [ ] Security Content Automation Protocol (SCAP)
- [ ] Benchmarks
- [ ] Agents/agentless
- [ ] Security information and event management (SIEM)
- [ ] Antivirus
- [ ] Data loss prevention (DLP)
- [ ] Simple Network Management Protocol (SNMP) traps
- [ ] NetFlow
- [ ] Vulnerability scanners

### 4.5 Given a scenario, modify enterprise capabilities to enhance security

**Firewall:**
- [ ] Rules
- [ ] Access lists
- [ ] Ports/protocols
- [ ] Screened subnets

**IDS/IPS:**
- [ ] Trends
- [ ] Signatures

**Web Filter:**
- [ ] Agent-based
- [ ] Centralized proxy
- [ ] Universal Resource Locator (URL) scanning
- [ ] Content categorization
- [ ] Block rules
- [ ] Reputation

**Operating System Security:**
- [ ] Group Policy
- [ ] SELinux

**Implementation of Secure Protocols:**
- [ ] Protocol selection
- [ ] Port selection
- [ ] Transport method

**Additional Security Enhancements:**
- [ ] DNS filtering
- [ ] Email security
  - [ ] DMARC
  - [ ] DKIM
  - [ ] SPF
  - [ ] Gateway
- [ ] File integrity monitoring
- [ ] DLP
- [ ] Network access control (NAC)
- [ ] Endpoint detection and response (EDR)/extended detection and response (XDR)
- [ ] User behavior analytics

### 4.6 Given a scenario, implement and maintain identity and access management

**User Account Management:**
- [ ] Provisioning/de-provisioning user accounts
- [ ] Permission assignments and implications
- [ ] Identity proofing

**Federation and SSO:**
- [ ] Federation
- [ ] Single sign-on (SSO)
  - [ ] Lightweight Directory Access Protocol (LDAP)
  - [ ] Open authorization (OAuth)
  - [ ] Security Assertions Markup Language (SAML)
- [ ] Interoperability
- [ ] Attestation

**Access Controls:**
- [ ] Mandatory
- [ ] Discretionary
- [ ] Role-based
- [ ] Rule-based
- [ ] Attribute-based
- [ ] Time-of-day restrictions
- [ ] Least privilege

**Multifactor Authentication:**
- [ ] Implementations
  - [ ] Biometrics
  - [ ] Hard/soft authentication tokens
  - [ ] Security keys
- [ ] Factors
  - [ ] Something you know
  - [ ] Something you have
  - [ ] Something you are
  - [ ] Somewhere you are

**Password Concepts:**
- [ ] Password best practices
  - [ ] Length
  - [ ] Complexity
  - [ ] Reuse
  - [ ] Expiration
  - [ ] Age
- [ ] Password managers
- [ ] Passwordless

**Privileged Access Management Tools:**
- [ ] Just-in-time permissions
- [ ] Password vaulting
- [ ] Ephemeral credentials

### 4.7 Explain the importance of automation and orchestration related to secure operations

**Use Cases of Automation and Scripting:**
- [ ] User provisioning
- [ ] Resource provisioning
- [ ] Guard rails
- [ ] Security groups
- [ ] Ticket creation
- [ ] Escalation
- [ ] Enabling/disabling services and access
- [ ] Continuous integration and testing
- [ ] Integrations and Application programming interfaces (APIs)

**Benefits:**
- [ ] Efficiency/time saving
- [ ] Enforcing baselines
- [ ] Standard infrastructure configurations
- [ ] Scaling in a secure manner
- [ ] Employee retention
- [ ] Reaction time
- [ ] Workforce multiplier

**Other Considerations:**
- [ ] Complexity
- [ ] Cost
- [ ] Single point of failure
- [ ] Technical debt
- [ ] Ongoing supportability

### 4.8 Explain appropriate incident response activities

**Process:**
- [ ] Preparation
- [ ] Detection
- [ ] Analysis
- [ ] Containment
- [ ] Eradication
- [ ] Recovery
- [ ] Lessons learned

**Training and Testing:**
- [ ] Training
- [ ] Testing
  - [ ] Tabletop exercise
  - [ ] Simulation

**Investigation and Analysis:**
- [ ] Root cause analysis
- [ ] Threat hunting

**Digital Forensics:**
- [ ] Legal hold
- [ ] Chain of custody
- [ ] Acquisition
- [ ] Reporting
- [ ] Preservation
- [ ] E-discovery

### 4.9 Given a scenario, use data sources to support an investigation

**Log Data:**
- [ ] Firewall logs
- [ ] Application logs
- [ ] Endpoint logs
- [ ] OS-specific security logs
- [ ] IPS/IDS logs
- [ ] Network logs
- [ ] Metadata

**Data Sources:**
- [ ] Vulnerability scans
- [ ] Automated reports
- [ ] Dashboards
- [ ] Packet captures

---

## Domain 5.0: Security Program Management and Oversight (20%)

### 5.1 Summarize elements of effective security governance

**Guidelines, Policies, and Standards:**
- [ ] Guidelines
- [ ] Policies
  - [ ] Acceptable use policy (AUP)
  - [ ] Information security policies
  - [ ] Business continuity
  - [ ] Disaster recovery
  - [ ] Incident response
  - [ ] Software development lifecycle (SDLC)
  - [ ] Change management
- [ ] Standards
  - [ ] Password
  - [ ] Access control
  - [ ] Physical security
  - [ ] Encryption

**Procedures:**
- [ ] Change management
- [ ] Onboarding/offboarding
- [ ] Playbooks

**External Considerations:**
- [ ] Regulatory
- [ ] Legal
- [ ] Industry
- [ ] Local/regional
- [ ] National
- [ ] Global

**Governance Structure:**
- [ ] Monitoring and revision
- [ ] Types of governance structures
  - [ ] Boards
  - [ ] Committees
  - [ ] Government entities
  - [ ] Centralized/decentralized

**Roles and Responsibilities:**
- [ ] Owners
- [ ] Controllers
- [ ] Processors
- [ ] Custodians/stewards

### 5.2 Explain elements of the risk management process

**Risk Identification and Assessment:**
- [ ] Risk identification
- [ ] Risk assessment
  - [ ] Ad hoc
  - [ ] Recurring
  - [ ] One-time
  - [ ] Continuous

**Risk Analysis:**
- [ ] Qualitative
- [ ] Quantitative
- [ ] Single loss expectancy (SLE)
- [ ] Annualized loss expectancy (ALE)
- [ ] Annualized rate of occurrence (ARO)
- [ ] Probability
- [ ] Likelihood
- [ ] Exposure factor
- [ ] Impact

**Risk Register:**
- [ ] Key risk indicators
- [ ] Risk owners
- [ ] Risk threshold

**Risk Tolerance and Appetite:**
- [ ] Risk tolerance
- [ ] Risk appetite
  - [ ] Expansionary
  - [ ] Conservative
  - [ ] Neutral

**Risk Management Strategies:**
- [ ] Transfer
- [ ] Accept
  - [ ] Exemption
  - [ ] Exception
- [ ] Avoid
- [ ] Mitigate

**Risk Reporting and BIA:**
- [ ] Risk reporting
- [ ] Business impact analysis
  - [ ] Recovery time objective (RTO)
  - [ ] Recovery point objective (RPO)
  - [ ] Mean time to repair (MTTR)
  - [ ] Mean time between failures (MTBF)

### 5.3 Explain the processes associated with third-party risk assessment and management

**Vendor Assessment:**
- [ ] Penetration testing
- [ ] Right-to-audit clause
- [ ] Evidence of internal audits
- [ ] Independent assessments
- [ ] Supply chain analysis

**Vendor Selection:**
- [ ] Due diligence
- [ ] Conflict of interest

**Agreement Types:**
- [ ] Service-level agreement (SLA)
- [ ] Memorandum of agreement (MOA)
- [ ] Memorandum of understanding (MOU)
- [ ] Master service agreement (MSA)
- [ ] Work order (WO)/statement of work (SOW)
- [ ] Non-disclosure agreement (NDA)
- [ ] Business partners agreement (BPA)

**Vendor Management:**
- [ ] Vendor monitoring
- [ ] Questionnaires
- [ ] Rules of engagement

### 5.4 Summarize elements of effective security compliance

**Compliance Reporting:**
- [ ] Internal
- [ ] External

**Consequences of Non-Compliance:**
- [ ] Fines
- [ ] Sanctions
- [ ] Reputational damage
- [ ] Loss of license
- [ ] Contractual impacts

**Compliance Monitoring:**
- [ ] Due diligence/care
- [ ] Attestation and acknowledgement
- [ ] Internal and external
- [ ] Automation

**Privacy:**
- [ ] Legal implications
  - [ ] Local/regional
  - [ ] National
  - [ ] Global
- [ ] Data subject
- [ ] Controller vs. processor
- [ ] Ownership
- [ ] Data inventory and retention
- [ ] Right to be forgotten

### 5.5 Explain types and purposes of audits and assessments

**Attestation:**
- [ ] Attestation process

**Internal:**
- [ ] Compliance
- [ ] Audit committee
- [ ] Self-assessments

**External:**
- [ ] Regulatory
- [ ] Examinations
- [ ] Assessment
- [ ] Independent third-party audit

**Penetration Testing:**
- [ ] Physical
- [ ] Offensive
- [ ] Defensive
- [ ] Integrated
- [ ] Known environment
- [ ] Partially known environment
- [ ] Unknown environment
- [ ] Reconnaissance
  - [ ] Passive
  - [ ] Active

### 5.6 Given a scenario, implement security awareness practices

**Phishing:**
- [ ] Campaigns
- [ ] Recognizing a phishing attempt
- [ ] Responding to reported suspicious messages

**Anomalous Behavior Recognition:**
- [ ] Risky
- [ ] Unexpected
- [ ] Unintentional

**User Guidance and Training:**
- [ ] Policy/handbooks
- [ ] Situational awareness
- [ ] Insider threat
- [ ] Password management
- [ ] Removable media and cables
- [ ] Social engineering
- [ ] Operational security
- [ ] Hybrid/remote work environments

**Reporting and Monitoring:**
- [ ] Initial
- [ ] Recurring

**Program Management:**
- [ ] Development
- [ ] Execution

---

## Study Resources

### Acronyms Reference
See the complete acronym list in the official objectives document for all 200+ acronyms.

### Practice Labs Equipment List
- Network devices: Routers, switches, firewalls, wireless APs
- Servers: Windows, Linux, web servers
- Security tools: IDS/IPS, SIEM, vulnerability scanners
- Virtual environments and cloud platforms
- Mobile devices and MDM software

### Exam Tips
1. Understand scenario-based questions thoroughly
2. Practice performance-based questions
3. Know the difference between similar concepts (e.g., IDS vs IPS)
4. Memorize common port numbers and protocols
5. Understand risk calculations (SLE, ALE, ARO)
6. Know incident response process order
7. Understand access control models
8. Practice with command-line tools
9. Know cryptographic algorithms and use cases
10. Understand compliance frameworks

---

## Study Progress Tracker

Track your progress through each domain:

| Domain | Topics Mastered | Practice Score | Ready for Exam |
|--------|----------------|----------------|----------------|
| 1.0 General Security Concepts | 0/4 | 0% | ❌ |
| 2.0 Threats, Vulnerabilities | 0/5 | 0% | ❌ |
| 3.0 Security Architecture | 0/4 | 0% | ❌ |
| 4.0 Security Operations | 0/9 | 0% | ❌ |
| 5.0 Program Management | 0/6 | 0% | ❌ |

**Overall Progress:** 0/28 objectives completed

---

## Notes Section

Add your study notes, mnemonics, and key takeaways here:
```
[Your notes]
```

---

*This study guide is based on CompTIA Security+ SY0-701 Exam Objectives Version 5.0*  
*Copyright © 2023 CompTIA, Inc. All rights reserved.*
