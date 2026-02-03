## 🌐 Certification Roadmap (Live Site)

Explore the **Interactive Certification Roadmap** published at:

➡️ https://hackthacker.github.io/Certification-Roadmap/

This roadmap provides a **visual and structured guide** to certifications and related paths across multiple cybersecurity domains.  
It serves as a **reference and planning tool** for learners and professionals mapping their certification journeys.

> 💡 *This is a guide, not a definitive path. Prices & requirements are estimates. Always verify information with the certification body. Based on the excellent original work by CyberSecurity teams.*

---

# 📜 Cybersecurity Certification Directory

A structured, community-driven repository of **cybersecurity and technology certifications**, organized by domain, level, and relevance.  
This project emphasizes **accuracy, consistency, and long-term maintainability**.


## 🎯 Project Objectives

- Maintain a centralized directory of recognized certifications
- Enforce a strict and immutable JSON schema
- Provide clear domain classification
- Enable professional, reviewable community contributions

---

## 📄 Certification JSON Schema

All certification entries **must** strictly follow the schema below.  
⚠️ **Do not modify keys, add fields, or alter the structure.**

```json
{
  "id": "cert_UNIQUE_NUMBER",
  "acronym": "ACRONYM",
  "fullName": "Full Name of Certification",
  "details": "Short Description (e.g., Free exam)",
  "href": "https://link-to-certification.com",
  "level": "Beginner/Intermediate/Advanced",
  "domainKey": "net/iam/eng/asset/mgmt/test/soft/ops"
}
```
## 🔍 Example Entry

```json
{
  "id": "cert_483",
  "acronym": "CND",
  "fullName": "Certified Network Defender",
  "details": "Vendor-neutral network defense certification",
  "href": "https://www.eccouncil.org/train-certify/certified-network-defender-cnd/",
  "level": "Intermediate",
  "domainKey": "net"
}

````


## 🧭 Supported Certification Domains

Only the following `domainKey` values are permitted.

| Key     | Domain Name                         | Short Name   | Focus Areas                                        |
| ------- | ----------------------------------- | ------------ | -------------------------------------------------- |
| `net`   | Communication & Network Security    | Network      | Network security, protocols, firewalls             |
| `iam`   | Identity & Access Management        | IAM          | Authentication, authorization, identity governance |
| `eng`   | Security Architecture & Engineering | Arch & Eng   | Cloud, SysOps, *nix, ICS, IoT                      |
| `asset` | Asset Security                      | Asset Sec    | Data protection, asset lifecycle                   |
| `mgmt`  | Security & Risk Management          | Risk & Mgmt  | Governance, Risk & Compliance (GRC)                |
| `test`  | Security Assessment & Testing       | Assessment   | Auditing, vulnerability assessment                 |
| `soft`  | Software Development Security       | Software Sec | Secure coding, SDLC                                |
| `ops`   | Security Operations                 | Operations   | Forensics, Incident Response, Pentesting           |

⚠️ Using undocumented or custom domain keys is **not allowed**.



## 📊 Certification Levels

Allowed values for `level`:

* `Beginner`
* `Intermediate`
* `Expert`

Choose the level based on the **expected experience and exam difficulty**.



## 🛠️ Contributing

Contributions are welcome and reviewed carefully.

### Contribution Requirements

* Unique certification ID
* Official certification URL
* Correct domain classification
* Proper level assignment
* Full schema compliance



## 🚫 Restrictions

* No schema changes
* No duplicate certifications
* No unofficial or broken links
* No removal or modification of attribution




## 📜 License & Attribution

This project is provided for educational and community use.

© 2026 by Hackthacker
hackthacker.blogspot.com



## 🙌 Acknowledgements

Thanks to all contributors who help maintain the quality, accuracy, and professionalism of this repository.
