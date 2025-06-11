---
title: "Lab Challenges"
permalink: /labchallenges
---

# Sharon Mwanje Lusega - Lab Challenges Portfolio
Hands-on cybersecurity labs from the **Microsoft ADC Cybersecurity Skilling Program** and personal CTF explorations.  

---

## 🔐 Microsoft Entra Conditional Access Policy  
**Problem**: Enforce secure access to Microsoft Admin portals by requiring MFA for specific users.  
**Approach**:  
1. Created a Conditional Access policy in Microsoft Entra ID targeting admin portal access.  
2. Configured policy to trigger MFA for users in the "Admin Access" group.  
3. Tested enforcement by attempting to sign in without MFA.  

**Tools**:  
`Microsoft Entra ID` `Conditional Access` `Multi-Factor Authentication (MFA)`  

**Key Lessons**:  
- Learned to balance security with usability by scoping policies to high-risk portals.  
- Verified policy effectiveness through real-time sign-in logs.  



---

## 🔄 Microsoft Entra Self-Service Password Reset (SSPR)  
**Problem**: Reduce IT overhead by enabling users to reset passwords securely.  
**Approach**:  
1. Enabled SSPR for a security group in Microsoft Entra ID.  
2. Registered test users with authentication methods (email/phone).  
3. Simulated password reset and reviewed audit logs.  

**Tools**:  
`Microsoft Entra SSPR` `Audit Logs` `Usage & Insights`  

**Key Lessons**:  
- SSPR requires clear user communication to ensure successful adoption.  
- Audit logs are critical for tracking compliance and troubleshooting.  

---

## ⚡ Privileged Identity Management (PIM)  
**Problem**: Minimize standing admin privileges to reduce attack surface.  
**Approach**:  
1. Assigned the *User Administrator* role with time-bound activation.  
2. Activated the role as a test user and performed group management.  
3. Monitored PIM alerts for unusual activations.  

**Tools**:  
`Microsoft Entra PIM` `Just-In-Time Access` `Role Templates`  

**Key Lessons**:  
- Time-bound roles enforce the principle of least privilege.  
- PIM requires Entra ID P2 licensing but significantly enhances security.  

---

## 🛡️ Cloud Security Demo Lab (Personal Project)  
**Problem**: Secure an Azure environment against common threats.  
**Approach**:  
1. Deployed VMs with NSGs and Azure Firewall.  
2. Implemented Conditional Access and MFA policies.  
3. Monitored threats using Microsoft Sentinel.  

**Tools**:  
`Azure NSGs` `Sentinel SIEM` `Azure Firewall` `Kali Linux`  

**Key Lessons**:  
- Layered defenses (firewalls + MFA + monitoring) are essential.  
- Sentinel provides centralized visibility into attacks.  

---

### 📌 Future Labs  
- **CTF Challenges**: Practicing on platforms like TryHackMe/HackTheBox.  
- **Azure Sentinel Threat Hunting**: Advanced SIEM queries.  

> *"The more you test, the more you learn."*  



