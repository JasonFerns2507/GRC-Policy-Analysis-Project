# GRC Project: Security Policy Gap Analysis

### Objective
This project demonstrates the process of performing a gap analysis on an existing corporate security policy in response to a new business initiative. The goal is to identify outdated or missing controls and recommend specific updates to strengthen the organization's governance posture. This is a foundational skill for any GRC or Information Security Analyst.

---

### 1. The Scenario
Innovate Inc., a fast-growing tech startup, has just approved a new "Bring Your Own Device" (BYOD) program. Starting next month, employees will be allowed to use their personal laptops and smartphones to access the company's internal network, email system, and cloud file storage (SharePoint). The goal is to increase flexibility and employee satisfaction. You have been asked to review the existing Acceptable Use Policy to see if it's ready for this change.

---

### 2. The Original Policy
The analysis was performed on the company's existing **Acceptable Use Policy (AUP)**.

[Link to the Original AUP Policy](./Original_AUP_Policy.md)

---

### 3. Gap Analysis Findings

* **Gap 1: Scope Limitation**
    * **Analysis:** The policy is explicitly scoped to "company-owned computers" (Section 2.0). It does not cover personal devices, making the entire policy unenforceable for the new BYOD program.
    * **Risk:** Without a clear policy scope, there is no legal or administrative basis to enforce security controls on employee-owned devices, creating a massive security and compliance blind spot.
 
* **Gap 2: Lack of Minimum Security Baselines for Devices**
    * **Analysis:** The policy does not mandate any specific security controls for the personal devices themselves. There are no requirements for device passcodes, biometrics, data encryption, VPN usage when on public Wi-Fi, or keeping the operating system updated.
    * **Risk:** An employee's unsecured personal device could be lost or stolen, providing an attacker with direct access to corporate data. Unpatched devices are also vulnerable to malware that could spread to the company network.
---

### 4. Recommendations & Revised Policy
*_(This is where we will summarize our recommendations)_*

[Link to the Revised AUP Policy](./Revised_AUP_Policy.md)
