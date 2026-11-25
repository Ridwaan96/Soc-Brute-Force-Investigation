SOC Incident Investigation: Brute Force Attack
Project Overview
This project documents the investigation of a brute force attack conducted in a SOC simulation environment.

The objective was to identify malicious authentication activity, determine whether the attack was successful, establish the timeline of events, analyze indicators of compromise (IOCs), map attacker actions to the MITRE ATT&CK framework, and provide remediation recommendations.

**Skills Demonstrated**
- Security Monitoring
- Log Analysis
- SIEM Investigation
- Incident Response
- Threat Detection
- MITRE ATT&CK Mapping
- IOC Analysis
- Report Writing
**Incident Summary**
A SIEM alert identified multiple failed authentication attempts against a user account. Investigation revealed repeated login failures originating from a suspicious source IP address. Log analysis was conducted to determine attack progression, affected assets, and potential impact.

**Investigation Process**
**Detection**
- Reviewed SOC alert
- Identified authentication anomalies
**Analysis**
- Examined failed login events
- Correlated successful authentication events
- Investigated source IP activity
**Containment**
- Documented response actions
- Identified security control improvements
**MITRE ATT&CK Mapping**
Brute Force	T1110
Valid Accounts	T1078
Remote Services (RDP)	T1021.001
**Key Findings**
- Identified attack source
- Determined targeted account
- Established attack timeline
- Assessed attack impact
- Recommended mitigation measures
**Tools Used**
LetsDefend
Wireshark
SIEM Platform
MITRE ATT&CK Framework
**Lessons Learned**
This investigation improved my ability to analyze authentication events, identify brute force attacks, build incident timelines, and document findings using professional SOC reporting standards.
