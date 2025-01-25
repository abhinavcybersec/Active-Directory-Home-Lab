# Project: Active Directory Home Lab
### Project Overview
This project showcases a virtual home lab designed to simulate a Windows Active Directory environment for hands-on learning in cybersecurity and threat detection. The lab integrates multiple systems and tools to provide a realistic setup for testing, monitoring, and analyzing security events.
---
### Environment Setup
1. Windows Server (Active Directory):
    - Configured as a domain controller for user and resource management.
2. Ubuntu Server (Splunk):
    - Serves as a SIEM platform to collect and analyze logs from the lab environment.
3. Windows 10 Machine:
    - Two users configured to simulate typical endpoint activity.
    - Splunk Universal Forwarder installed for log forwarding.
    - Sysmon activated to capture detailed event logs.
    - Atomic Red Team installed for generating attack telemetry.
4. Kali Linux Machine:
    - Used to simulate attacks against the Windows 10 system.
    - Conducted brute force attacks using Crowbar to test detection capabilities.
---
### Key Features
- **Active Directory Simulation:** A realistic domain environment for exploring authentication, user management, and access control.
- **Security Event Monitoring:** Logs are forwarded to Splunk for real-time monitoring and analysis.
- **Attack Simulation:** Simulated adversarial activities using Kali Linux and Atomic Red Team.
- **Threat Detection Practice:** Enhanced skills in analyzing attack patterns and detecting malicious activity within an enterprise environment.
---
### Use Cases
- Understanding Active Directory structure and configurations.
- Testing and improving security event monitoring with a SIEM (Splunk).
- Practicing threat detection and response strategies in a controlled lab environment.
