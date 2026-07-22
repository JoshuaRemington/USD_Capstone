# USD Capstone: Securing Design World - A Comprehensive Cybersecurity Engineering Project
Program: Master of Science in Cybersecurity Engineering, University of San Diego (USD)

Courses: CYBR-514 (Cyber Engineering Research I) & CYBR-516 (Cyber Engineering Research II)

Status: Near completion (3 additional assignments pending)

This repository documents my capstone project for the USD MS in Cybersecurity Engineering program. It demonstrates the application of cybersecurity engineering principles to secure a fictional multi-domain international enterprise called Design World, based on a realistic case study provided in the program.

The project simulates real-world enterprise security challenges across a three-city international structure with multiple subnets (Business, Public, Website, Transit/Services), diverse operating systems (Windows Server 2022, Ubuntu, CentOS), services (Domain Controller, File Server, Web Server, VPN), and an AI platform component.

### Project Overview

Design World is a private international company requiring a full Information Systems Security Plan. The capstone involves:

Requirements gathering and risk assessment

Vulnerability assessments (using tools like Nessus)

Penetration testing planning

Threat modeling and architecture-driven security

System hardening across heterogeneous environments

Secure architecture design, including network segmentation, VPN, and VLANs

AI/ML system security considerations (in CYBR-516)

Project Change Requests (PCRs) for hardening implementations

Security reporting and documentation

The goal is to reduce risk to an acceptable level in a virtual lab environment while aligning with best practices, standards (e.g., NIST), and engineering rigor.

### Repository Structure

    USD_Capstone

    ├── CYBR-514/                  # Core traditional IT security deliverables (Group 1)
    │   ├── Group 1 Assignment 1.2_ System Security Requirements Report.pdf
    │   ├── Group 1 Assignment 2.1_ Vulnerability Assessment Plan_Rev2.pdf
    │   ├── Group 1 Assignment 3.1_ Vulnerability Assessment Report.pdf
    │   ├── Group 1 Assignment 3.2_ Penetration Testing Plan.pdf
    │   ├── Group 1 Assignment 5.1_ Security Hardening Plan and PCR.pdf
    │   └── Group 1 Assignment 7.1_ Security Hardening Report with Updated Designs.pdf
    │
    ├── CYBR-516/                  # AI-focused and advanced architecture deliverables
    │   ├── Assignment 1.1_Design World AI Platform Case Review...
    │   ├── Assignment 1.2_ AI Systems & Security Requirements Report.pdf
    │   ├── Assignment 2.1_ Architecture Review Findings.pdf
    │   ├── Assignment 2.2_ Secure Architecture Guide + Diagrams.pdf
    │   ├── Assignment 3.1_ Architecture-Driven Threat Enumeration.pdf
    │   └── Assignment 4.1 - Secure AI SDLC & Assurance Readiness.pdf
    │
    ├── Nessus Scans/              # Vulnerability scan results
    │   ├── Business Subnet_...
    │   ├── Public Subnet_...
    │   ├── Transit and Services VLAN_...
    │   └── Website Subnet_...
    │
    ├── PCRs/                      # Project Change Requests (hardening implementations)
    │   ├── PCR-001_ Windows Server 2022 Domain Controller Hardening.pdf
    │   ├── PCR-002_ Windows Server 2022 File Server Hardening.pdf
    │   ├── PCR-003_ Ubuntu 22.04 Workstation Hardening.pdf
    │   ├── PCR-004_ CentOS Stream 9 Web Server Hardening.pdf
    │   └── PCR-005_ OpenVPN and Transit VLAN Hardening.pdf
    │
    ├── DesignWorldAIArchitecture.pdf
    ├── DesignWorldVPCArchitecture.png
    ├── LICENSE
    └── README.md

### Key Deliverables and Achievements

Phase 1: Requirements & Assessment (CYBR-514)

Developed System Security Requirements aligned with business objectives.

Created a Vulnerability Assessment Plan and executed scans with Nessus across subnets.

Produced detailed Vulnerability Assessment Reports identifying issues.

Planned Penetration Testing activities.

Phase 2: Hardening & Implementation

Authored Project Change Requests (PCRs) for targeted hardening of:

Windows Domain Controller & File Server

Ubuntu Workstation

CentOS Web Server

OpenVPN and network segmentation (Transit VLAN)

Updated system designs and network diagrams post-hardening.

Documented Security Hardening Report with before/after comparisons.

Phase 3: Advanced & AI Security (CYBR-516)

Reviewed AI Platform case elements and security requirements.

Developed Secure Architecture Guide with diagrams.

Performed Architecture-Driven Threat Enumeration.

Addressed Secure AI SDLC and assurance processes.

Pending Assignments: Three more deliverables will be added as completed (likely final integration, testing, or presentation materials).

### Technologies & Tools Used

Scanning: Nessus (vulnerability assessments)

OS/Platforms: Windows Server 2022, Ubuntu 22.04, CentOS Stream 9

Networking: OpenVPN, VLANs, subnet segmentation

Documentation: Professional reports, diagrams, change management

Security Frameworks: NIST, secure SDLC, threat modeling, risk management

### Learning Outcomes & Skills Demonstrated

This capstone integrates the full USD Cybersecurity Engineering curriculum, including:

Risk assessment and security requirements engineering

Vulnerability management and ethical hacking principles

Secure system design and network engineering

Incident handling foundations

AI/ML system security considerations

Professional documentation, teamwork, and change control

It emphasizes engineering rigor — not just identifying problems, but designing, implementing, verifying, and documenting solutions in a simulated enterprise environment.

### Future Enhancements (Planned)

Add final reports and integration testing results

Add scripts/config snippets for hardening (where permissible)

Expand AI security section with any additional labs

### License

This repository is licensed under the LICENSE file. This work is not to be redistributed or used for private or public purposes. This project is meant to bring knowledge and show the research, understanding, and effort performed during my group's USD capstone.

### Acknowledgments

University of San Diego Shiley-Marcos School of Engineering

Christian Calipusan, Brian Che, O.Kingsley Ero, Mikalou Nikiema, Mohammad Ahmed, and Shivam Patel

"Design World" case study creators


### Repository Author: Joshua Remington

Feel free to explore the documents. This project showcases practical, end-to-end cybersecurity engineering for enterprise environments.

Last updated: July 2026 (will be refreshed with remaining assignments)