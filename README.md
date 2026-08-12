# Telehealth Cybersecurity Risk Assessment (NIST RMF & HIPAA)

A comprehensive cybersecurity risk register and assessment program developed for a cloud-first telehealth startup. This project demonstrates the operationalization of the **NIST Risk Management Framework (RMF)** to secure Patient Health Information (PHI) and ensure strict regulatory alignment with the **HIPAA Security Rule**.

## 🎯 Project Overview

**Scenario:** *SecurePulse* is a 10-person, fully remote healthcare technology startup whose mission is to provide secure, real-time video consultations between doctors and patients. 

Handling highly sensitive electronic Patient Health Information (ePHI) in a remote, cloud-based environment presents a massive attack surface. The objective of this project was to transition the organization from an immature, ad-hoc security posture into a formal, risk-based management framework. By identifying critical business assets and mapping threats, this project strategically selects and applies controls to reduce residual risk to an acceptable business level.

## 💼 Business Value & GRC Application

- **Regulatory Compliance:** Directly aligns startup operations with the HIPAA Security Rule, mitigating the risk of severe federal fines and protecting patient trust.
- **Data-Driven Decision Making:** Translates technical vulnerabilities (e.g., unencrypted video streams, endpoint compromise) into quantified business risks (Likelihood vs. Impact), allowing leadership to prioritize security investments.
- **Secure Remote Operations:** Addresses the unique threat landscape of a 100% remote workforce handling sensitive ePHI across distributed endpoints and cloud infrastructure.

## 🛠️ Methodology & Framework Execution

This assessment closely follows the NIST Risk Management Framework lifecycle:

**1. Asset Inventory & Categorization**
- Cataloged primary and supporting assets (Cloud databases, remote employee laptops, video-conferencing APIs).
- Classified data flows to track exactly where ePHI is stored, transmitted, and processed.

**2. Risk Identification (Threat Modeling)**
- Identified relevant threat actors (insider threats, ransomware operators) and vulnerabilities (weak IAM, unpatched endpoints, insecure home Wi-Fi networks).

**3. Risk Analysis & Quantification**
- Conducted a qualitative risk analysis calculating Inherent Risk based on the Likelihood of occurrence and the Business Impact (Confidentiality, Integrity, and Availability).

**4. Risk Treatment & Mitigation**
- Designed a targeted Risk Treatment Plan (Mitigate, Transfer, Avoid, or Accept).
- Mapped specific administrative, physical, and technical safeguards to the identified risks.

**5. Residual Risk Assessment**
- Evaluated the remaining risk after control implementation to ensure it falls within the startup's defined risk appetite.

## 📂 Project Structure

```text
Telehealth-Risk-Assessment/
├── 01_Asset_Inventory/
│   └── SecurePulse_Asset_Data_Flow.xlsx
├── 02_Risk_Register/
│   └── HIPAA_NIST_Risk_Register.xlsx
├── 03_Risk_Treatment/
│   └── Mitigation_and_Control_Plan.pdf
├── 04_Policies/
│   └── Remote_Work_ePHI_Policy.pdf
└── README.md
