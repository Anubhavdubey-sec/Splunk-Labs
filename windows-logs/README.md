# Windows Log Analysis Labs

This directory contains Splunk labs focused on Windows security telemetry, event logs, process activity, authentication, and endpoint investigation.

## Topics

### Windows Event Logs

- Event ID 4624 — Successful Logon
- Event ID 4625 — Failed Logon
- Event ID 4688 — Process Creation
- Event ID 4672 — Special Privileges Assigned
- Event ID 7045 — Service Installation

### Process Analysis

- Process creation
- Parent-child process relationships
- Suspicious command lines
- Unusual executables
- Process execution patterns

### PowerShell

- PowerShell execution
- Suspicious commands
- Encoded commands
- Script execution
- PowerShell investigation

### Endpoint Investigation

- User activity
- Host activity
- Persistence indicators
- Privilege escalation indicators
- Suspicious process behavior

## SPL Skills

Labs will demonstrate:

- Event filtering
- Field extraction
- `stats`
- `table`
- `timechart`
- `rex`
- `eval`
- `where`
- Event correlation

## Investigation Questions

Typical questions include:

- Which user generated the event?
- Which host was affected?
- What process was executed?
- What was the parent process?
- What command line was used?
- When did the activity occur?
- Was the activity expected?
- Are there related events?

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
