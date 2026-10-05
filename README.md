# 🛡️ AUTHENTIX v2.1.0 Enterprise Showcase

**Next-Generation Authentication, IDOR/BOLA & Secret Scanner Security Suite for Burp Suite**

[![Enterprise Portal](https://img.shields.io/badge/Enterprise%20Portal-Live%20Showcase-c8a96e?style=for-the-badge&logo=shield)](https://pratik-khairnar-sec.github.io/authentix-enterprise/)
[![Author](https://img.shields.io/badge/Author-Pratik%20Khairnar-38bdf8?style=for-the-badge&logo=github)](https://github.com/pratik-khairnar-sec)
[![Montoya API](https://img.shields.io/badge/Burp%20Suite-Montoya%20API-FF6633?style=for-the-badge&logo=portswigger)](https://portswigger.net/burp)
[![Java](https://img.shields.io/badge/Java-17%20%7C%2021-ED8B00?style=for-the-badge&logo=openjdk)](https://openjdk.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

---

### 🌐 Live Executive Portal & Slide Deck
👉 **[https://pratik-khairnar-sec.github.io/authentix-enterprise/](https://pratik-khairnar-sec.github.io/authentix-enterprise/)**

---

## 📌 Executive Summary

**AUTHENTIX v2.1.0** is an enterprise-grade security extension for PortSwigger Burp Suite (built natively on the **PortSwigger Montoya API**) engineered to address the critical gaps in modern Application Security testing:
- **Broken Object Level Authorization (BOLA / IDOR)**
- **Multi-Step Authentication & MFA Lifecycle Flaws**
- **Compound Account Takeover (ATO) Attack Chains**
- **Deep Client-Side JavaScript & HTTP Secret Scanning**

It continuously models actor lifecycle states as a deterministic finite-state automaton, validates **27 formal mathematical security invariants**, runs **28 deep secret analysis rules**, maintains an automated **Cross-Actor Authorization Matrix**, and broadcasts real-time push alerts to security teams via the **Telegram Bot API**.

---

## 🔬 Core Capabilities

| Feature | Description | Status |
|---|---|---|
| 🎯 **IDOR & BOLA Engine** | Auto-detects sequential/UUID IDs, maps cross-actor access matrices | ✅ Live |
| 🛡️ **27 Security Invariants** | Deterministic state machine checks (OTP, session, JWT, IDOR, BFLA) | ✅ Live |
| 🔬 **28 File & Secret Rules** | Scans for AWS, GCP, Azure, OpenAI, Anthropic, Firebase, Stripe, JWT keys | ✅ Live |
| ⛓️ **12 Attack Chain Rules** | Correlates multi-step findings into complete ATO Kill Chains | ✅ Live |
| 📱 **Telegram Bot Dispatcher** | Real-time mobile alerts with terminal-ready Kali cURL PoC commands | ✅ Live |
| 🏦 **NimbusBank v2 Lab** | Full enterprise banking portal with 16 planted exploit vectors | ✅ Live |
| ⚡ **Zero UI Latency** | Asynchronous multi-threaded worker pools | ✅ Live |

---

## 🌐 Live Demonstration Portal

Explore the interactive security demonstration, 27 Invariants simulation, 28 secret rules engine, and full Montoya API architecture:
👉 **[Launch AUTHENTIX Enterprise Portal](https://pratik-khairnar-sec.github.io/authentix-enterprise/)**

---

## 📂 Documentation & Engineering Artifacts

- 📑 **[Formal Project Report (PDF)](docs/reports/AUTHENTIX_Project_Report.pdf)**: Comprehensive 20+ page engineering specification covering architecture, threat models, finite-state machine proofs, and verification logs.
- 🎓 **[Formal Research Paper (PDF)](docs/reports/AUTHENTIX_Research_Paper.pdf)**: Academic-grade research paper: *"Deterministic Finite-State Invariant Verification for Multi-Step Authentication & IDOR Vulnerabilities in Web APIs"*.
- 📊 **[Executive Presentation Slides (PDF)](docs/reports/AUTHENTIX-Presentation-Slides.pdf)**: Print-ready 11-slide presentation summarizing executive findings, NimbusBank test lab results, and enterprise deployment options.
- 📄 **[Author ATS Resume (PDF)](docs/reports/Pratik_Khairnar_Resume_ATS.pdf)**: Professional single-page security engineer resume of Pratik Khairnar.

---

## 👤 Author & Architecture Inquiries

**Pratik Khairnar**
- GitHub: [@pratik-khairnar-sec](https://github.com/pratik-khairnar-sec)
- Cyber Security Researcher & Security Tool Developer

---

## 📄 License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
