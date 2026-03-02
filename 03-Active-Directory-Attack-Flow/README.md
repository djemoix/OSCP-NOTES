# Active Directory Attack Flow
**Author: Manish Verma**

---

## 📌 Objective

Document structured Active Directory exploitation workflows for authorized penetration testing engagements.

**Scope:** Internal network environments with Active Directory  
**Tools Used:** BloodHound, Impacket, CrackMapExec, Rubeus, Mimikatz  
**Outcome:** Domain Compromise / Domain Admin Access  

---

## 🔍 Enumeration Phase

```bash
# Enumerate users, groups, and domain info
enum4linux -a <target>
nmap -sV -p 389,445,88,135 <target>
```

---

## ⚔️ Attack Techniques

### AS-REP Roasting
- Target accounts with "Do not require Kerberos preauthentication"
- Extract hashes and crack offline

### Kerberoasting
- Request service tickets for SPN accounts
- Crack TGS hashes to obtain service account passwords

### BloodHound Analysis
- Collect AD data using SharpHound
- Identify attack paths to Domain Admin

### ACL Abuse
- Exploit misconfigured Access Control Lists
- GenericAll, WriteDACL, GenericWrite privileges

### DCSync Attack
- Replicate domain credentials using Directory Replication Service
- Requires Replicating Directory Changes permissions

### Pass-the-Hash (PTH)
- Use NTLM hash for lateral movement
- No need to crack password

### Domain Dominance
- Golden Ticket / Silver Ticket attacks
- Persistence via scheduled tasks, registry

---

## 🎯 Goal

Simulate real-world Active Directory attack scenarios to understand defensive gaps and improve detection capabilities.
