## Security Philosophy: Lab Environment & The CIA Triad

My virtualization lab is designed as a controlled, self-contained system, prioritizing security through isolation. This setup directly aligns with the **CIA Triad** (Confidentiality, Integrity, and Availability). By utilizing virtualization, I'm able to ensure **Confidentiality** through logical isolation; the guest operating systems are sandboxed from my host machine. This prevents uauthorized data leakage between the environments. **Integrity** is maintained through teh use of snapshots, allowing for a verifiable state that protects against any accidental or malicious modifications. Lastly, **Availability** is addressed by the accessibility of virtual machines, which can be backed up and restored quickly if there was a system failure for example. 
### Security Foundations: Governance & Frameworks

#### CIA Triad
The CIA Triad are the goals of cybersecurity professionals. It balances Confidentiality (ensures that the authorized user can see particular information) Integrity (ensures that the information hasnt been modified and is trustworthy) and Availability(the idea that authorized users have access to the information they need when they need it).

#### The AAA Framework
The AAA Framework is the process of managing identity. It consists of Authentication (verifies who you are) Authorization (determines what you are allowed to do), and Accounting (monitors and audits the access request). 

#### Governance in Cybersecurity

Governance refers to how the organization governs the way things are done. It dictates what is acceptable behavior. Can employees access files at home? Is it best practice to lock your work computer while you arent using it? Are these standards accepted as an organization. As cybersecurity practitioners, the goal is to protect data and its users. Governance provides a structured way of managing this data so that if there is a cybersecurity risk, it can be managed appropriately. 

**APA Citation:** National Institute of Standards and Technology.(2018). Framework for improving Critical Infrastructure Cybersecurity. https://doi.org/10.6028/NIST.CSWP.04162018

Chapple, M., & Seidl, D. (2024). Comptia Security+ Study Guide: Exam SY0-701. Sybex. 

**Reflection:** Without governance, technical tools are just random tools without a goal. Governance establishes a framework that helps organizations guide the actions of cybersecurity practitioners. It makes sure that their efforts are aligned with teh objectives of the organization. GRC is the security domain that aligns most with today's material. When we discuss teh CIA, AAA, and the NIST cybersecurity framework, it all touches on how we manage cybersecurity risk. 

## Lab Report: Professional Identity & Workbench Setup

**Student:** Jasmine Newton
**Course:** Cybersecurity Foundations Intensive
**Date:** February 23, 2026
**Instructor:** Night 1 Faculty

---

## Technical Environment Summary
This repository serves as the primary version-controlled portfolio for the 2026 Cybersecurity Ecosystem. 

### Metrics & Specifications 
**Editor:** VS Code v1.9x
**VCS:** Git 2.4x
**Host:** GitHub (Private Repository)
**Documentation Standard:** APA 7th Edition
