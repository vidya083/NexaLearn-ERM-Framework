# NexaLearn Inc. - Enterprise Risk Management (ERM) Framework

## 📋 Overview
This repository contains a comprehensive, end-to-end implementation of an **Enterprise Risk Management (ERM)** framework modeled for a cloud-native Software-as-a-Service (SaaS) Learning Management System (LMS) provider, **NexaLearn Inc.** (supporting 520,000+ active global students and 20,000+ faculty members).

Recent high-profile security incidents targeting the educational ecosystem such as the **Canvas LMS credential outbreaks** orchestrated by threat groups like ShinyHunters demonstrate that cloud-native environments can no longer treat risk management as a static compliance check. 

This project bridges the gap between GRC theory and active defense by simulating a structured compliance and threat-modeling roadmap built from the ground up, utilizing international security standards including **ISO/IEC 27001:2022 (Clause 4)** and **NIST CSF 2.0**.

---

## 🏗️ Repository Architecture
The framework is structured into functional, lifecycle-oriented phases to replicate an authentic corporate security engineering deployment:

* 📁 **[01-Governance-and-Scoping](./01-Governance-and-Scoping)**
  * Establishes the organizational context, enterprise mission, stakeholder expectations, defined system boundaries (**In-Scope vs. Out-of-Scope**), and legal/regulatory compliance obligations under **FERPA** and **GDPR**.
* 📁 **[02-Asset-Management](./02-Asset-Management)**
  * Registers and classifies both tangible and intangible assets (Data, Software, Hardware, Network, and Brand Reputation). Maps assets back to their principal **CIA Triad** objectives and dictates relative qualitative business impact scores.
* 📁 **[03-Threat-Modeling](./03-Threat-Modeling)**
  * Maps the current threat horizon to inherent application and process vulnerabilities. Establishes specialized **Threat/Vulnerability Pairs** modeling credential stuffing vectors and lateral ransomware exploit pathways.
* 📁 **[04-Risk-Assessment](./04-Risk-Assessment)**
  * Executes a quantitative risk priority matrix utilizing empirical mathematical scoring ($Risk = Likelihood \times Impact$) to define organizational risk thresholds and construct an objective remediation roadmap.

---

## 🔍 Core Methodologies & Standards Used
* **ISO/IEC 27001:2022:** Guided the "Context of the Organization" scoping definitions and the asset management lifecycle layout.
* **NIST CSF 2.0:** Applied to structure asset classifications, operational profiles, and critical impact thresholds.
* **Quantitative Risk Analysis:** Utilized a standard 1–5 likelihood and impact rating convention to mathematically derive risk scores (1–25) and establish critical business priorities over subjective assumptions.

