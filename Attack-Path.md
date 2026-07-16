# Attack Path

## Phase 1

Reconnaissance

- Nmap
- Service Enumeration

---

## Phase 2

Kerberos Enumeration

Tool:

Kerbrute

Objective:

Identify valid domain users.

---

## Phase 3

AS-REP Roasting

Tool:

GetNPUsers.py

Objective:

Identify accounts without Kerberos pre-authentication.

---

## Phase 4

Password Cracking

Tool:

Hashcat

Hash Mode:

18200

Recovered:

svc-admin credentials

---

## Phase 5

SMB Enumeration

Tool:

smbclient

Recovered:

backup credentials

---

## Phase 6

Credential Dumping

Tool:

secretsdump.py

Method:

DRSUAPI

Recovered:

NTDS.DIT password hashes

---

## Phase 7

Pass-the-Hash

Tool:

Evil-WinRM

Recovered:

Administrator shell
