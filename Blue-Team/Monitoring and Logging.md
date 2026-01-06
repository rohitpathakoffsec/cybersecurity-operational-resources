# Monitoring & Logging Tools

Tools and platforms used for **network monitoring, traffic inspection,
audit logging, incident detection, and runtime security**.

---

## Audit Logging & Compliance

- **BoxyHQ** – Open-source API for security and compliance audit logging.

---

## Network Traffic Capture & Logging

- **justniffer** – Network protocol analyzer that captures traffic and generates
  customizable logs. Can emulate Apache-style logs, track response times, and
  extract files from HTTP traffic.
- **httpry** – Lightweight packet sniffer designed for capturing, parsing, and
  logging HTTP traffic in real time or as a background daemon.
- **ngrep** – PCAP-aware network grep tool that applies regular or hexadecimal
  expressions to packet payloads. Supports IPv4/6, TCP, UDP, ICMP, and more.
- **passivedns** – Tool for passively collecting DNS records to support incident
  handling, NSM, and digital forensics. Supports live capture and PCAP analysis
  with aggregation to reduce log volume.

---

## Log Analysis & Detection

- **Sagan** – Log analysis engine using Snort-like rules to analyze syslog,
  event logs, SNMP traps, and NetFlow data.

---

## Network Visibility & Analytics

- **ntopng** – Network traffic probe that provides real-time visibility into
  network usage, similar to the Unix `top` command for processes.

---

## Cloud-Native Runtime Security

- **Falco** – Cloud-native runtime security and Kubernetes threat detection
  engine, part of the CNCF ecosystem.
