# Alert Data Sources

1. **MITRE ATT&CK Framework**:
   - T1059.001 (PowerShell / In-Memory Execution): Alerts M02, M05
   - T1003 (OS Credential Dumping): Alert M02
   - T1486 (Data Encrypted for Impact / Vssadmin): Alert M04
   - T1105 (Ingress Tool Transfer via Certutil): Alert M05
   - T1078.002 (Domain Accounts Privilege Escalation): Alert M06

2. **CISA Known Exploited Vulnerabilities (KEV) Catalog**:
   - Reference patterns for edge device exploitation and CVE-2024-3400 telemetry (Alerts M01, M07).

3. **Enterprise Defense Telemetry Baselines**:
   - CrowdStrike Falcon / Windows Security Event Log Event IDs 4624, 4625 (Logon Telemetry: Alerts M08, M10).
   - Tenable Nessus Vulnerability Scanner standard reporting templates (Alert M07).
   - EICAR Standard Anti-Virus Test File Specification (Alert M09).