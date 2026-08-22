# Network Log Analysis Labs

This directory contains Splunk labs focused on network telemetry, DNS activity, network connections, traffic patterns, and suspicious network behavior from a SOC perspective.

## Topics

### Network Connections

- Source and destination analysis
- Port analysis
- Protocol analysis
- Connection frequency
- Unusual outbound connections

### DNS

- DNS query analysis
- Suspicious domains
- High-frequency queries
- NXDOMAIN analysis
- Potential DNS tunneling indicators

### Network Threats

- Port scanning
- Suspicious outbound traffic
- Command-and-control indicators
- Beaconing patterns
- Data transfer anomalies

### Traffic Analysis

- Top source IPs
- Top destination IPs
- Top ports
- Protocol distribution
- Time-based traffic analysis

## SPL Skills

Labs will demonstrate:

- `stats`
- `timechart`
- `top`
- `rare`
- `eval`
- `where`
- `sort`
- `rex`
- Field filtering
- Event correlation

## Investigation Questions

Typical questions include:

- Which hosts generated the most connections?
- Which destinations were contacted?
- Which ports were targeted?
- Which protocols were used?
- Are there unusual connection patterns?
- Is there evidence of scanning?
- Is there evidence of command-and-control behavior?
- Are there unusual DNS patterns?
- What evidence supports the finding?

## Lab Format

Each completed lab should contain:

1. Scenario
2. Investigation objective
3. Dataset
4. SPL query
5. Query explanation
6. Results
7. Evidence
8. Analysis
9. Finding
10. Detection opportunity
11. MITRE ATT&CK mapping where applicable
12. Lessons learned

## Status

Labs will be added progressively using authorized training datasets.
