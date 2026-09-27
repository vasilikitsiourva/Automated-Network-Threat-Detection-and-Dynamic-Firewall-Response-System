# Automated Network Defense

A network security project that combines intrusion detection with automated firewall response.

## Goal

The system will monitor network traffic using Suricata, process security alerts, calculate a threat score, and dynamically apply firewall rules using nftables.

## Planned Architecture

Network Traffic  
↓  
Suricata IDS  
↓  
Alert Processor  
↓  
Threat Scoring Engine  
↓  
Firewall Response  
↓  
nftables

## Planned Features

- Suricata alert monitoring
- Parsing of `eve.json`
- Threat scoring
- Temporary IP blocking
- nftables integration
- Logging and audit history
- Network security dashboard

## Technologies

- Python
- Suricata
- nftables
- Linux
- Git / GitHub

## Status

Early development.