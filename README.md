CyberHawk: Real-Time Network Threat Hunter Using ELK & Snort

CyberHawk is a fully virtualized SOC environment designed to demonstrate real-time threat detection, log analysis, and adversary behavior monitoring using the ELK Stack and Snort IDS. The project simulates realistic enterprise attack scenarios by integrating multi-VM log collection, Snort-based network intrusion detection, and centralized SIEM workflows. It analyzes events from Windows and Linux systems, correlates malicious activity, and visualizes attack patterns through dynamic Kibana dashboards. Throughout the project, several real-world attack behaviors were reproduced, including:

• Failed login brute-force attempts and unauthorized user creation
• Suspicious PowerShell execution and registry modification events
• Malicious PCAP replay using tcpreplay to trigger Snort alerts
• Detection of malware communication patterns such as Remcos RAT and IcedID

These events were ingested using Winlogbeat and Filebeat, parsed through Logstash with GROK patterns, and indexed into Elasticsearch for threat hunting. The project demonstrates end-to-end SOC operations—from log ingestion and IDS alerting to investigation and visualization—providing a strong practical foundation for understanding SIEM architecture, intrusion detection, and coordinated threat response.
