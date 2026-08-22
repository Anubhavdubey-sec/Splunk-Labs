# Splunk Dashboards

This directory contains Splunk dashboards designed to visualize security events, monitor trends, support investigations, and provide SOC analysts with actionable security information.

## Objective

Dashboards should transform raw security telemetry into useful visual context for investigation and monitoring.

## Planned Dashboards

### Authentication Dashboard

Metrics:

- Total authentication attempts
- Successful logins
- Failed logins
- Top source IPs
- Top targeted accounts
- Authentication activity over time

### Web Security Dashboard

Metrics:

- Total HTTP requests
- Requests by status code
- Top source IPs
- Top URLs
- HTTP methods
- User-Agent distribution
- Suspicious request trends

### Network Security Dashboard

Metrics:

- Network connections
- Top source IPs
- Top destinations
- Top ports
- Protocol distribution
- DNS activity
- Suspicious outbound connections

### Windows Security Dashboard

Metrics:

- Authentication events
- Process creation
- PowerShell activity
- Privileged activity
- Suspicious process patterns

### Threat Hunting Dashboard

Metrics:

- Suspicious indicators
- Rare events
- High-risk activity
- Authentication anomalies
- Network anomalies

## Dashboard Design Principles

A useful SOC dashboard should:

- Prioritize actionable information
- Show trends over time
- Highlight anomalies
- Provide useful filtering
- Support investigation workflows
- Avoid unnecessary visual noise

## Dashboard Documentation

Each completed dashboard should contain:

1. Dashboard objective
2. Data sources
3. Important metrics
4. SPL searches
5. Visualization explanation
6. Investigation use case
7. Screenshots
8. Findings
9. Lessons learned

## Status

Dashboards will be added progressively as corresponding Splunk labs and datasets are completed.
