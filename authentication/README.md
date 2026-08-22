# Authentication Labs

This directory contains Splunk labs focused on authentication activity, account security, and detecting suspicious login behavior.

## Topics

### Authentication Failures

- Failed login analysis
- Repeated authentication failures
- Source IP analysis
- Targeted account analysis
- Login failure trends

### Brute Force

- Detecting repeated login attempts
- Identifying attacking source IPs
- Time-based analysis
- Threshold-based detection
- False-positive analysis

### Password Spraying

- Multiple accounts targeted from one source
- Low-and-slow authentication attacks
- Account targeting patterns
- Detection logic

### Successful Authentication

- Successful login after repeated failures
- Unusual login locations
- Unusual authentication times
- Suspicious account activity

## SPL Skills

Labs in this category will demonstrate:

- `search`
- `stats`
- `timechart`
- `where`
- `eval`
- `sort`
- `dedup`
- Field filtering
- Time-range analysis
- Event correlation

## Lab Format

Each completed lab should contain:

1. Scenario
2. Investigation objective
3. Dataset
4. SPL query
5. Query explanation
6. Results
7. Analysis
8. Finding
9. Detection opportunity
10. MITRE ATT&CK mapping
11. Lessons learned

## Investigation Questions

Typical questions include:

- Which source IP generated the most failed logins?
- Which accounts were targeted?
- When did the activity occur?
- Was a successful login observed after failures?
- Does the activity indicate brute force or password spraying?
- Are there legitimate explanations?
- What detection could identify the behavior?

## Status

Labs will be added progressively using authorized training datasets.
