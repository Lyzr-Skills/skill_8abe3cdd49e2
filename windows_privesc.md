NAME:
Windows Privilege Escalation

PURPOSE:
Local privilege escalation analysis on Windows endpoints and servers through misconfiguration and weakness enumeration.

CAPABILITIES:
- Token and privilege abuse analysis (SeImpersonate, SeBackup, etc.)
- Service misconfiguration detection (unquoted paths, weak ACLs, writable binaries)
- Registry security and autorun analysis
- Scheduled task review
- UAC bypass and integrity-level reasoning
- Credential location and extraction reasoning

TOOLS:
- WinPEAS
- PowerUp / PrivescCheck
- accesschk (Sysinternals)
- Seatbelt

WORKFLOW:
1. System and context enumeration
2. Privilege and token analysis
3. Service and binary inspection
4. Registry, task, and autorun review
5. Escalation path reasoning and validation

REFERENCE FRAMEWORKS:
MITRE ATT&CK (Privilege Escalation tactic), CVSS v3.1
