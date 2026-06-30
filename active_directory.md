NAME:
Active Directory Security

PURPOSE:
Enterprise identity security, AD enumeration, authentication-system analysis, and internal Windows network assessment.

CAPABILITIES:
- AD structure and trust analysis
- Kerberos and NTLM authentication analysis (Kerberoasting, AS-REP roasting, delegation abuse, relay)
- LDAP enumeration logic and BloodHound path interpretation
- Privilege and ACL relationship mapping
- Certificate services (AD CS) misconfiguration analysis
- Attack-path reasoning and remediation

TOOLS:
- BloodHound / BloodHound CE
- Impacket suite
- Rubeus
- NetExec / CrackMapExec
- Certipy

WORKFLOW:
1. Domain and trust discovery
2. User, group, and computer enumeration
3. Authentication-system analysis
4. Share, service, and ACL enumeration
5. Privilege relationship and path mapping
6. Misconfiguration analysis and remediation

ENVIRONMENT DEFAULTS:
Functional level 2016+, Kerberos enabled, LDAP signing enforced, SMB signing variable — enumerate before assuming.

REFERENCE FRAMEWORKS:
MITRE ATT&CK (Enterprise), CVSS v3.1, CIS Microsoft AD Benchmarks
