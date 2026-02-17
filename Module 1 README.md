# 1.1 Cybersecurity Overview

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

# 1.2 Cyber Threats and Vulnerabilities

## 📌 Introduction

Cyber threats are malicious attempts to access, damage, or disrupt digital systems by exploiting vulnerabilities in software, networks, or human behavior. Understanding these threats helps organizations build stronger defenses and protect critical information.

---

## 🧨 Types of Cyber Threats

### Insider Threats

Threats originating from authorized individuals within an organization such as employees or contractors.
They may intentionally misuse access or accidentally expose sensitive data.

**Types**
 * Malicious employee stealing data
 * Negligent user exposing credentials
 * Compromised insider account
   
**Impact**
 * Data theft
 * Sabotage
 * Intellectual property loss

**Why dangerous**
Insiders already have access privileges.

**Mitigation**
 * Access monitoring
 * Least privilege
 * Behavior analytics

**Key Point:** Trusted access can become a security risk.

---

### Phishing

A social engineering technique where attackers trick users into revealing sensitive information through fake messages or websites.

**Methods**
 * Fake emails
 * Malicious links
 * Spoofed websites

**Variants**
 * Spear phishing (targeted)
 * Whaling (executives)
 * Smishing (SMS)
 * Vishing (voice)

**Impact**
 * Credential theft
 * Malware installation

**Defense**
 * User awareness
 * Email filtering
 * Multi-factor authentication
   
**Key Point:** Targets human trust rather than technical weaknesses.

---

### Supply Chain Attacks

Attacks that compromise third-party vendors or software dependencies to reach the main target system.

**How it works**
Instead of attacking the target directly:
 * Malware inserted into updates
 * Vendor credentials stolen
 * Dependency poisoning

**Impact**
 * Large-scale infiltration
 * Hard to detect

**Defense**
 * Vendor audits
 * Code signing
 * Dependency scanning

**Key Point:** Exploits trusted relationships and distribution channels.

---

### Malware

Malicious software designed to harm systems or steal data.

**Examples**

* Virus
* Worm
* Trojan
* Ransomware
* Spyware

**Effects**
 * Data destruction
 * Surveillance
 * Encryption for ransom

**Defense**
 * Antivirus
 * Sandboxing
 * Updates

**Key Point:** Used for disruption, surveillance, or financial gain.

---

### Advanced Persistent Threats (APTs)

Sophisticated long-term attacks conducted by skilled adversaries, often targeting strategic assets.

**Key Characteristics**

* Stealthy
* Persistent
* Highly targeted

**Attack Lifecycle**
 1. Initial intrusion
 2. Lateral movement
 3. Data exfiltratio
 4. Long-term persistence

**Actors**
Often nation-states or elite groups.

**Key Point:** Focus on prolonged infiltration rather than immediate damage.

---

## 🌍 Real-World Case Studies

### Equifax Breach (2017)

Attackers exploited an unpatched vulnerability to access sensitive consumer data.

**Type:** Web vulnerability exploitation

**What happened**
 * Unpatched web application vulnerability
 * Attackers accessed sensitive consumer data

**Impact**
 * Data of millions exposed
 * Massive legal and financial consequences

**Lessons**
 * Patch management critical
 * Vulnerability scanning essential

---

### WannaCry Ransomware (2017)

A worm-based ransomware attack that encrypted systems globally.

**Type:** Worm-based ransomware

**What happened**
 * Exploited Windows SMB vulnerability
 * Rapid global spread

**Impact**
 * Hospitals shut down
 * Critical systems locked

**Lessons**
 * Timely updates vital
 * Backup strategy required

---

## 🛰 Nation-State APT Examples

### Stuxnet

Advanced malware targeting industrial control systems.

**Characteristics**
 * Highly advanced malware 
 * Physical system disruption
 * Precision targeting 

**Significance:** Demonstrated cyberattacks can cause physical damage.

---

### SolarWinds Attack

Supply chain compromise through malicious software updates.

**Type:** Supply chain compromise
**Method**
 * Malicious code inserted into software update
 * Spread to many organizations

**Significance:** Showed the large-scale impact of trusted software infiltration.

---


