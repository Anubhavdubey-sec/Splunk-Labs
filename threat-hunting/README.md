# Threat Hunting Labs

This directory contains Splunk-based threat hunting exercises focused on proactively identifying suspicious activity that may not have generated an existing security alert.

## Objective

Threat hunting begins with a hypothesis and uses available telemetry to search for evidence of malicious or abnormal behavior.

## Hunting Workflow

```text
Hunting Hypothesis
        ↓
Identify Required Telemetry
        ↓
Build SPL Query
        ↓
Search Historical Data
        ↓
Identify Anomalies
        ↓
Correlate Evidence
        ↓
Validate Findings
        ↓
Determine Verdict
        ↓
Create Detection Opportunity
