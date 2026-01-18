# LexUNA: Open-Source Legal Wrapper for DAOs

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Legal: UNA](https://img.shields.io/badge/Entity-Unincorporated%20Non--Profit-orange.svg)](#)
[![Ecosystem: Public Good](https://img.shields.io/badge/Ecosystem-DAO%20Infrastructure-purple.svg)](https://stellar.org)

**LexUNA** is a standardized, code-first repository of legal templates for **Unincorporated Non-Profit Associations (UNA)**. It is designed specifically for developer collectives and DAOs that require a legal identity to sign contracts, hire contributors, or open bank accounts without the friction and expense of traditional corporate incorporation.

---

### 1. Executive Summary
Most developer collectives operate in a "legal gray area." Without a formal structure, members may be personally liable for the group's debts or actions. LexUNA provides a "Legal-as-Code" solution. We translate complex statutes into plain-English, modular templates that allow a DAO to adopt a UNA structure. This provides the group with "Legal Personhood"—enabling it to act as a single entity in the eyes of the law—while maintaining its decentralized ethos.

### 2. The Problem
The path to legality for Web3 projects is currently blocked by:
* **The Incorporation Tax:** Registering an LLC or C-Corp is expensive, requires recurring fees, and often mandates a centralized board of directors.
* **Liability Exposure:** Unwrapped DAOs are often legally classified as "General Partnerships," meaning every token holder could be held personally liable for a protocol exploit or debt.
* **Institutional Friction:** You cannot sign a lease for a hacker house or open a traditional bank account as a "Smart Contract Address."

### 3. Key Features
* **📄 Modular UNA Templates:** Pre-vetted Articles of Association and Bylaws that can be customized for specific DAO governance models.
* **⚖️ Liability Shielding:** Guidance on how to properly structure a UNA to protect individual members from the collective's liabilities.
* **🏦 Institutional Onboarding Kit:** Standardized documentation packages designed to be "Bank-Ready" and "Contract-Ready" for real-world interactions.
* **🔗 Governance Mapping:** Templates that explicitly link on-chain voting results (Snapshot/Soroban) to legally binding corporate actions.

### 4. Roadmap for this Wave
* **Phase 1:** Release the "Genesis Template" optimized for US-based Unincorporated Nonprofit Association Acts.
* **Phase 2:** Develop the "Governance Bridge"—legal language that recognizes smart contract calls as official "Member Resolutions."
* **Phase 3:** Expand the library to include "International UNA" equivalents (e.g., European Associations) to support global collectives.

### 5. Why LexUNA belongs in Drips Wave
LexUNA is an **Institutional Public Good**.
* **Protects Builders:** We lower the barrier for developers to protect themselves legally while they build innovative tech.
* **Sustainability:** We use Drips to stream 15% of our funding to legal-tech researchers and open-source legal advocacy groups who fight for developer rights.

---

## 🛠 Project Structure

```text
LexUNA/
├── templates/
│   ├── articles-of-association/ # Core legal formation documents
│   ├── bylaws/                  # Operational rules for members
│   └── service-agreements/      # Templates for hiring DAO contributors
├── docs/
│   ├── guides/                  # Plain-English walkthroughs of the law
│   └── jurisdiction-matrix/     # Comparison of UNA laws across regions
├── scripts/
│   └── generator.js             # Simple CLI to fill templates via terminal
└── LICENSE                      # MIT Licensed


````
👨‍💻 Disclaimer
LexUNA provides legal templates, not legal advice. Use of these templates does not create an attorney-client relationship. We strongly recommend having your final documents reviewed by a qualified professional in your jurisdiction.
