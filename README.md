# OSCP Preparation Knowledgebase

A focused, evolving knowledgebase for preparing for practical penetration-testing work and OSCP-style labs.

> This repository documents study notes and lab practice only. It does **not** indicate OSCP certification, exam completion, or endorsement by Offensive Security.

## Start here

- [Navigation](NAVIGATION.md)
- [Roadmap](ROADMAP.md)
- [Enumeration checklist](CHECKLISTS/ENUMERATION.md)
- [Lab note template](TEMPLATES/LAB-NOTE.md)
- [Reporting template](TEMPLATES/REPORT.md)
- [Ethical scope notes](ETHICS-AND-SCOPE.md)

## Existing notes

| Path | Current material |
| --- | --- |
| [01-Recon](01-Recon/README.md) | ExifTool, DNS, NetBIOS, SNMP and SMTP enumeration notes |
| [03-Active-Directory-Attack-Flow](03-Active-Directory-Attack-Flow/README.md) | High-level AD assessment flow and enumeration reference |
| [FTP ENUMERATION](FTP%20ENUMERATION/) | Legacy scratch directory; review before relying on it |

Existing content is preserved. New material makes the collection easier to navigate and more consistent as notes grow.

## Suggested study loop

1. Define target, authorization and timebox.
2. Enumerate broadly, then validate the most promising paths.
3. Keep commands, timestamps, assumptions and evidence together.
4. Explain why a technique worked, not only which command worked.
5. Record defensive visibility and remediation alongside offensive observations.
6. Re-test from a clean starting point and write a concise report.

## Note quality standard

Prefer reproducible notes with target and scope, prerequisites, exact commands with placeholders, expected versus observed output, sanitized evidence, hypothesis and conclusion, cleanup, and a defensive takeaway.

Never commit real credentials, tokens, customer data, private keys, malware, or sensitive target information.

## Disclaimer

Use these materials only in systems you own or are explicitly authorized to assess. Follow the rules of engagement for every lab, course, client and exam environment. Stop when scope or authorization is unclear.
