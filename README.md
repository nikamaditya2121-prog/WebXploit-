# WebXploit

## Web Application Attack Simulation & Defense Toolkit

WebXploit is an isolated cybersecurity laboratory designed to simulate
common web application attacks and demonstrate their detection,
blocking, logging, monitoring, and incident-response workflow.

## Project Objective

The project integrates offensive and defensive security components
into a controlled environment for practical security testing.

## Architecture

Kali Linux
    ↓
Nginx + ModSecurity + OWASP CRS
    ↓
OWASP Juice Shop
    ↓
WAF Logs
    ↓
Filebeat
    ↓
Elasticsearch
    ↓
Kibana

## Attack Scenarios

- Cross-Site Scripting (XSS)
- SQL Injection
- Network Reconnaissance
- Command Injection
- Path Traversal

## Technologies

- Kali Linux
- Ubuntu Server
- Docker
- Docker Compose
- Nginx
- ModSecurity
- OWASP CRS
- OWASP Juice Shop
- Filebeat
- Elasticsearch
- Kibana
- Nmap
- cURL
- VMware

## Security Workflow

Attack Simulation
→ Detection
→ Blocking
→ Logging
→ Telemetry
→ Monitoring
→ Investigation
→ Incident Response

## Results

The implemented WAF detected and blocked the tested XSS,
SQL injection, command injection and path traversal requests,
returning HTTP 403 responses.

Network reconnaissance was observed through service and
security telemetry.

## Laboratory Environment

The project was implemented in an isolated VMware laboratory
using Kali Linux and Ubuntu Server.

## Documentation

The complete academic project report is available in:

`reports/WebXploit-Final-Report.pdf`

## Disclaimer

This project is intended strictly for authorized cybersecurity
education, laboratory testing and defensive security research.

Do not use the techniques against systems without explicit
authorization.

## Future Improvements

- Improved Filebeat ingestion
- Advanced Kibana dashboards
- Custom detection rules
- Automated attack simulations
- MITRE ATT&CK mapping
- Automated incident response
