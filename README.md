# SOC Home Lab

A containerized Security Operations Center lab demonstrating the full workflow:

**Telemetry → Detection → Triage → Response**

## Goal
Build a small SIEM lab that collects logs from a Kali Linux VM, detects suspicious activity with custom rules, and documents an incident response process.

## Tech Stack
- **SIEM:** Wazuh (Docker)
- **Log source:** Kali Linux VM (auditd + Wazuh agent)
- **Detection:** Sigma-style YAML rules
- **Alerting:** Wazuh dashboard

## Status
🚧 In progress — Week 1: lab setup.

## Documentation
- [Week 1 Setup](docs/week1-setup.md)
- [Project Journal](journal.md)
