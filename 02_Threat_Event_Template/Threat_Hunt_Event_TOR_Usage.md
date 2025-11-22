# Threat Event Template – TOR Usage Scenario

> **Purpose:** Document simulated malicious TOR activity and map related IoCs and detection logic.

## 👤 Analyst Information
- Name:  Matthew Faustino-Page
- Email:  mfaustino4786@gmail.com
- Date:  11/22/2025

---

# 1. Scenario Summary
Management suspects that some employees may be using TOR browsers to bypass network security controls because recent network logs show unusual encrypted traffic patterns and connections to known TOR entry nodes. Additionally, there have been anonymous reports of employees discussing ways to access restricted sites during work hours. The goal is to detect any TOR usage and analyze related security incidents to mitigate potential risks.

---

# 2. Environment
- Device Name:  matt-threat-hunt
- OS:  Windows 10 Enterprise x64 Gen2
- MDE Onboard Status:  Onboarded

---

# 3. Activity Steps (Adversary Emulation)
(Duplicate the “bad actor” steps here exactly.)

---

# 4. Generated IoCs
List:
- File artifacts  
- Process names  
- Network connections  
- Registry changes  
- Hashes  

---

# 5. Detection Logic

### Tables Referenced:
(List tables such as DeviceProcessEvents, DeviceNetworkEvents, etc.)

### Queries Used:
(Add KQL queries relevant to TOR detection.)

---

# 6. Findings Summary
Summarize how well IoCs showed up and how activity was detected.

---

# 7. MITRE ATT&CK Mapping
Examples:
- T1090 – Proxy Use
- T1071 – Application Layer Protocol

---

# 8. Recommendations
Add defensive steps or hardening strategies.
