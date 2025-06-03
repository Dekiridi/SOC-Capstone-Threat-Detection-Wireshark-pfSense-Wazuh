# SOC Threat Detection and Incident Response Capstone

## Overview
This repository contains the deliverables for a cybersecurity capstone project focused on **threat detection** and **incident response** using a combination of industry-standard tools: **Wireshark**, **pfSense**, and **Wazuh**. The simulation exercise was conducted to replicate real-world cyber threats such as brute-force attacks, unauthorized access, and suspicious outbound traffic within a controlled network environment.

## Project Details

- **Organization**: SoCra Tech
- **Role**: Security Operations Center (SOC) Analyst
- **Analyst**: David Kiridi
- **Date**: April 25, 2025

## Tools Used
- **Wireshark**: For network packet capture and traffic analysis (HTTP, DNS, SSH protocols).
- **pfSense**: Deployed as a firewall and IDS/IPS with Snort for traffic filtering, blocking, and alerting.
- **Wazuh**: Configured as a centralized SIEM for log correlation, event monitoring, and threat detection.
- **Kali Linux**: Used for threat simulation including brute-force SSH attacks.

## Methodology
The project was executed in multiple structured phases:
1. **Wireshark** – Capturing and analyzing network traffic anomalies.
2. **pfSense** – Setting up firewall rules, IDS/IPS (Snort), and GeoIP blocking to mitigate attacks.
3. **Wazuh** – Real-time monitoring and alert correlation for endpoint and network logs.

## Key Findings
- Successful detection of simulated brute-force SSH attacks.
- Identification of suspicious DNS and HTTP traffic indicating potential data exfiltration.
- Firewall effectively blocked unauthorized access attempts.
- Wazuh SIEM provided actionable alerts and log analysis for incident response validation.

## Recommendations
- Implement SSH key-based authentication.
- Regularly update Snort rule sets.
- Employ GeoIP filtering to block traffic from high-risk regions.
- Enable automated response rules in Wazuh for critical alerts.
- Maintain centralized and secure log management for compliance and auditing.

## Screenshots
- Wireshark captures of suspicious traffic.
- pfSense firewall rules and Snort alerts.
- Wazuh dashboards showing incident detections.



## Project Structure
```plaintext
├── Wireshark_Analysis
│   └── Screenshots, PCAPs, and Traffic Logs
├── pfSense_Configuration
│   └── Firewall Rules, Snort Alerts, and Logs
├── Wazuh_Monitoring
│   └── Dashboard Screenshots, Alert Logs
├── Final_Report
│   └── David_Kiridi_SOC_Capstone.pdf
├── README.md

