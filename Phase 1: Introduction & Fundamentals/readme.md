## **Phase 1: Introduction & Fundamentals**
**Goal:** Understand what OSSTMM is, its purpose, and its structure.

### **What is OSSTMM?**
The **Open Source Security Testing Methodology Manual (OSSTMM)** is an industry-recognized, scientific, and metrics-based approach to security testing. It focuses on:
- Measuring **operational security**.
- Identifying **trust relationships**.
- Providing a **standardized and repeatable testing framework**.

#### **Why OSSTMM?**
- Unlike **OWASP** or **PTES**, OSSTMM is **not just a checklist**. 
- It provides a **scientific way to measure security posture** through **metrics (RAV)**.
- Covers **five key channels of security testing**:
  1. Human Security
  2. Physical Security
  3. Wireless Communications
  4. Telecommunications
  5. Data Networks

#### **Real-world Use Cases:**
- Pentesting for enterprises.
- Auditing compliance (ISO 27001, HIPAA, PCI-DSS).
- Network security assessments.
- Quantifying risk for management.

---

### **Core OSSTMM Concepts**

#### **Five Channels of Security Testing**
1. **Human Security:** Focuses on human interaction, social engineering, insider threats.
2. **Physical Security:** Building access, CCTV blind spots, RFID testing.
3. **Wireless Communications:** Wi-Fi, Bluetooth, NFC security.
4. **Telecommunications:** VoIP, PBX, telephone systems.
5. **Data Networks:** Network-level pentesting, firewall assessments.

#### **RAV (Risk Assessment Values)**
The RAV formula helps **quantify security**:
```
RAV = (Visibility + Access + Trust) - Controls
```
Where:
- **Visibility (V):** How visible the assets are to attackers.
- **Access (A):** How easy it is to interact with the system.
- **Trust (T):** Unverified trust relationships.
- **Controls (C):** Mitigation measures implemented.

#### **STAR Reports**
The **Security Test Audit Report (STAR)** is a standardized reporting format for OSSTMM-based assessments. It ensures:
- Consistency.
- Clear communication with stakeholders.
- Compliance alignment.

---

## **OSSTMM Key Terms (Simplified)**
### **Attack Surface**
The total **exposed areas** of a system where an attacker can interact.
> *Think of it as all the open doors and windows of a house.*


---


### **Attack Vector**
A **smaller, specific part of the attack surface**, used to **organize testing step-by-step**.
> *Example: If the attack surface is a whole house, a vector is just the front door.*


---


### **Controls**
Measures taken to **reduce damage or loss** if an attack happens.
There are two types:
- **Class A Controls:** Directly protect assets (e.g., locks, firewalls).
- **Class B Controls:** Procedures or processes (e.g., incident response plan).


> *Example: Insurance for a store is a control. It doesn’t stop theft, but covers the loss.*


---


### **Limitations**
**Weak points** in a system that reduce security. These can be identified or proven through testing.
> *Example:*
> - **Identified Limitation:** Seeing an old, rusty lock and knowing it’s weak.
> - **Verified Limitation:** Testing the lock and finding it breaks with only 100 kg of force when 1000 kg is required.


---


### **Operations**
The **necessary openness** a system must have to function and be useful.
> *Example: A shop needs to keep its doors open for customers, even though it increases risk.*


---


### **Perfect Security**
The **ideal balance** between:
- Security
- Controls
- Operations
- Limitations


> *In reality, perfect security is impossible, but it’s the goal to aim for.*


---
### **Porosity**
All the **interaction points** in a system, grouped into:
- **Visibility:** What can be seen by outsiders.
- **Access:** What can be interacted with.
- **Trust:** What is trusted without verification.


> *Example: A login page has visibility (URL visible), access (form interaction), and trust (user credentials).*


---


### **Safety**
Protection where **effects of a threat are controlled** to an acceptable level.
> *Example:* Fire alarms don’t stop a fire but reduce its impact by alerting people early.


---


### **Security**
Protection where **threats are completely separated** from assets.
> *Example:* A firewall blocking malicious traffic before it reaches a server.*


---


### **RAV (Risk Assessment Value)**
A **score to measure the attack surface**, based on how balanced the system is between porosity, limitations, and controls.
- **100 RAV = Perfect balance**
- **< 100 RAV = Too few controls → More risk**
- **> 100 RAV = Too many controls → Added complexity**


> *Goal: Stay as close to 100 as possible.*


---


### **Target**
The **specific asset** or system being tested, including its protections.
> *Example:* A web server you’re assessing is the target.


---


### **Vector**
The **direction or pathway** an interaction takes during an attack.
> *Example:* Sending a phishing email to steal login credentials.*


---
