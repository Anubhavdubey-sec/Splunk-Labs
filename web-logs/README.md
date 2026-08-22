# Web Log Analysis Labs

This directory contains Splunk labs focused on HTTP activity, web server logs, suspicious requests, web attacks, and application security monitoring.

## Topics

### HTTP Analysis

- HTTP methods
- GET and POST requests
- HTTP status codes
- Request frequency
- Source IP analysis
- User-Agent analysis
- URL analysis

### Web Attacks

- SQL injection indicators
- Cross-site scripting indicators
- Path traversal
- Command injection indicators
- Authentication attacks
- Suspicious file requests

### Error Analysis

- HTTP 4xx responses
- HTTP 5xx responses
- Repeated server errors
- Suspicious request patterns

### Traffic Analysis

- Top source IPs
- Most requested URLs
- Request frequency
- User-Agent analysis
- Geographic patterns where data supports it
- Time-based attack patterns

## SPL Skills

Labs will demonstrate:

- `stats`
- `timechart`
- `top`
- `rare`
- `eval`
- `where`
- `rex`
- Field filtering
- Pattern analysis
- Time-based correlation

## Investigation Questions

Typical questions include:

- Which IP generated the most requests?
- Which HTTP methods were used?
- Which URLs were targeted?
- Which User-Agent generated suspicious traffic?
- Which status codes increased during the activity?
- Are there indicators of automated scanning?
- Are there indicators of exploitation?
- What evidence supports the conclusion?

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
