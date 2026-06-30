NAME:
Linux Privilege Escalation

PURPOSE:
Local privilege escalation analysis on Linux/Unix systems through enumeration of misconfigurations and weaknesses.

CAPABILITIES:
- SUID/SGID binary abuse analysis
- sudo and sudoers misconfiguration analysis
- cron job and scheduled-task exploitation logic
- kernel version and known-CVE risk analysis
- file/directory permission and capability issues
- environment and PATH abuse, writable service files

TOOLS:
- LinPEAS / linux-smart-enumeration
- GTFOBins (reference)
- pspy
- find / getcap (native enumeration)

WORKFLOW:
1. System and context enumeration
2. Permission, capability, and ownership analysis
3. Service, cron, and timer review
4. Misconfiguration and known-CVE detection
5. Escalation path reasoning and validation

REFERENCE FRAMEWORKS:
MITRE ATT&CK (Privilege Escalation tactic), CVSS v3.1
