# Lessons Learned

This project demonstrated how a sequence of small weaknesses can lead to full Active Directory compromise.

Key takeaways include:

- Kerberos user enumeration can reveal valid domain accounts.
- AS-REP Roasting exposes accounts configured without Kerberos pre-authentication.
- Weak passwords remain vulnerable to offline cracking.
- SMB shares may unintentionally expose sensitive credentials.
- DRSUAPI replication permissions can be abused to extract NTDS.DIT password hashes.
- Pass-the-Hash enables authentication without knowing the plaintext password.
- Monitoring authentication events, SMB activity, and replication requests is critical for detecting Active Directory attacks.

This exercise reinforced the importance of secure account configuration, least-privilege access, strong password policies, and continuous monitoring within enterprise environments.
