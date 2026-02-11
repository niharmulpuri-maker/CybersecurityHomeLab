# CybersecurityHomeLab
Established a localized Security Operations Center (SOC) environment to monitor Linux endpoints and engineer custom Detection & Response (D&R) rules using LimaCharlie EDR.

Tech Stack:

Hypervisor: UTM (Apple Silicon/ARM64)

Endpoint: Ubuntu Server 24.04 LTS

EDR: LimaCharlie

Telemetry: Auditd (Linux Auditing System)

Project Highlights:

Telemetry Ingestion: Configured auditd to monitor sensitive file integrity and piped logs via LimaCharlie Artifact Collection.

Detection Engineering: Authored a YAML-based D&R rule to detect unauthorized access to /etc/secret_data.txt.

Traffic Analysis: Investigated background DNS noise (Firefox telemetry) to establish a baseline for "normal" network activity.
