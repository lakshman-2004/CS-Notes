# Cybersecurity Overview

The fundamentals of cybersecurity including its scope, importance, and core principles. It also includes conceptual diagrams, real-world attack case studies, and curated learning resources.

This repository is designed for academic learning, portfolio demonstration, and introductory training in cybersecurity.

---

## 🌐 What is Cybersecurity?

Cybersecurity is the practice of protecting systems, networks, and data from digital attacks. It ensures that sensitive information remains secure, reliable, and accessible.

### Scope Includes

* **Network Security** — Protecting internal networks from intrusions
* **Application Security** — Securing software from vulnerabilities
* **Information Security** — Protecting data confidentiality
* **Cloud Security** — Safeguarding cloud-hosted assets
* **Endpoint Security** — Protecting user devices (PCs, mobiles)
* **Operational Security** — Policies & procedures for handling data
* **Disaster Recovery & Business Continuity**

### Impact in Today’s Digital Age

We live in a hyper-connected world where:
  * Banking, healthcare, education, government, and businesses are digital
  * Massive amounts of sensitive data are stored online
  * Cyberattacks can cause financial loss, privacy violations, and national security threats

Cybersecurity is now ```not optional — it’s critical infrastructure protection.```

---

## ❗ Why Cybersecurity Matters

### 🔹 Data Breaches

Unauthorized access to confidential data resulting in:

* Financial loss
* Privacy violations
* Reputation damage

### Typical causes:
  * Weak passwords
  * Misconfigured servers
  * Phishing attacks

### 🔹 Identity Theft

Attackers steal personal information to impersonate individuals.

### Consequences:
  * Fraudulent bank transactions
  * Fake loan applications
  * Social media misuse

### Common methods:
  * Phishing emails
  * Malware
  * Public Wi-Fi interception

### 🔹 Infrastructure Protection

Critical services such as power grids, hospitals, and transportation rely on cybersecurity for continuous operation.
  * Power grids
  * Transportation
  * Hospitals
  * Government networks

A cyberattack here can disrupt entire societies.

**Example threats:**
  * Ransomware locking hospital systems
  * DDoS attacks stopping services
  * Industrial sabotage
    
---

## 🔐 CIA Security Triad

### Confidentiality

Protects data from unauthorized access.

**Protection Methods:**
  * Encryption
  * Authentication
  * Access control
    
**Real-world example:**
  * Data leaks exposing private user data
  * Unauthorized viewing of company documents

**If broken →**
Privacy violation and data exposure.

### Integrity

Maintains accuracy and trustworthiness of data.

**Protection Methods:**
  * Hashing
  * Digital signatures
  * Version control
    
**Real-world example:**
  * Malware altering financial records
  * Attackers modifying database entries

**If broken →**
Trust in data is lost.

### Availability

Ensures systems and data remain accessible.

**Protection Methods:**

  * Redundancy
  * Load balancing
  * Backup systems

**Real-world example:**

  * Ransomware locking files
  * DDoS attacks shutting down websites
    
**If broken →**
Services stop functioning.

---

## 📊 Diagrams

### CIA Triad Conceptual Diagram

```
            +------------------+
            | Confidentiality  |
            +------------------+
                    /\
                   /  \
                  /    \
                 /      \
+------------------+   +------------------+
|    Integrity     |   |    Availability  |
+------------------+   +------------------+
```

---

### Basic Cybersecurity Protection Model

```
User → Firewall → IDS/IPS → Secure Network → Database
                ↑
           Monitoring
```

---

### Attack Surface Representation

```
[Internet]
     |
     v
[Router] -- [Web App] -- [Database]
     |
 [User Devices]

Potential Targets:
- Web vulnerabilities
- Credential theft
- Data interception
```

---

## 🧠 Attack Case Studies

### Case Study 1 — Equifax Data Breach

* Attack Type: Web Application Vulnerability
* Impact: Personal data of millions exposed
* Lesson Learned:

  * Patch management is critical
  * Vulnerability scanning must be continuous

---

### Case Study 2 — WannaCry Ransomware

* Attack Type: Ransomware Worm
* Impact:

  * Hospitals and businesses disrupted
  * Global operational shutdowns
* Lesson Learned:

  * System updates are essential
  * Backup strategies save organizations

---

### Case Study 3 — Twitter Social Engineering Attack

* Attack Type: Social Engineering
* Impact:

  * High-profile account compromise
* Lesson Learned:

  * Human security awareness matters
  * Access controls should be strict

---

## 📚 References & Learning Resources

### Books

* The Web Application Hacker’s Handbook
* Cybersecurity Essentials
* Hacking: The Art of Exploitation

### Online Platforms

* OWASP Learning Resources
* TryHackMe
* Hack The Box
* Coursera Cybersecurity Courses

