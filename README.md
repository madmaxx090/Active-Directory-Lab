# Active Directory Attack Simulation Lab

## Overview

This project documents a complete Active Directory attack simulation performed in a controlled lab environment. The objective was to understand how attackers enumerate, compromise, and escalate privileges within an enterprise Windows domain while identifying detection opportunities for SOC analysts.

---

## Objectives

- Enumerate Active Directory users
- Perform Kerberos user enumeration
- Exploit AS-REP Roasting
- Crack Kerberos hashes
- Enumerate SMB shares
- Recover exposed credentials
- Dump NTDS.DIT credentials
- Perform Pass-the-Hash authentication
- Obtain Domain Administrator access

---

## Lab Environment

| Machine | Role |
|---------|------|
| Kali Linux | Attacker |
| Windows Server | Domain Controller |

Domain:

spookysec.local

---

## Attack Chain

Reconnaissance

↓

Kerberos User Enumeration

↓

AS-REP Roasting

↓

Password Cracking

↓

SMB Enumeration

↓

Credential Discovery

↓

NTDS Extraction (DRSUAPI)

↓

Pass-the-Hash

↓

Administrator Access

---

## Tools

- Nmap
- Kerbrute
- Impacket
- Hashcat
- smbclient
- Evil-WinRM

---

## MITRE ATT&CK

See:

MITRE-Mapping.md

---

## Detection Opportunities

See:

Detection-Opportunities.md

---

## Screenshots

Available inside:

Screenshots/

---

## Disclaimer

This project was performed in a legal lab environment for educational purposes.
