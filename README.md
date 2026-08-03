# Security-Onion_Final
Sophia vieni
## Tool Overview
Security Onion is a free, open-source Linux distribution built specifically for network security monitoring, threat hunting, and log management. The tool can be used for network visibility, host visibility, intrusion detection honeypots, log management, and case management.

Security Onion can successfully monitor all these areas by combining several tools:
Suricata — an intrusion detection engine that flags known-bad traffic using signatures (like a antivirus for network traffic)
Zeek (formerly Bro) — logs detailed metadata about every network connection, so you can see what happened even without a specific alert
Wazuh — monitors individual hosts/endpoints for suspicious activity
Elasticsearch + Kibana — stores all those logs and alerts and lets you search/visualize them in a web dashboard
CyberChef — a Swiss-army-knife utility for decoding data (base64, hex, etc.) found in traffic
