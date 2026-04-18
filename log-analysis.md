# Log Analysis & Threat Detection

## Objective
The objective of this project was to analyze system and authentication logs to identify suspicious activity and understand how attackers attempt unauthorized access.

## Tools Used
- TryHackMe lab environment
- Basic log files (Linux authentication logs / system logs)

## Methodology
- Reviewed log entries to identify failed and successful login attempts
- Analyzed timestamps and frequency of login attempts
- Identified unusual patterns such as repeated access attempts from the same source
- Correlated log activity to determine potential attack behavior

## Sample Log Indicators
- Multiple failed login attempts within a short time period
- Repeated access attempts from a single IP address
- Logins occurring at unusual or unexpected times

## Key Findings
- Detected patterns consistent with brute-force login attempts
- Identified abnormal login behavior indicating possible unauthorized access attempts
- Observed how attackers rely on repeated attempts to gain access

## Security Implications
- Brute-force attacks can compromise accounts with weak credentials
- Monitoring logs is critical for early detection of suspicious activity
- Implementing account lockout policies and alerts can reduce risk

## What I Learned
- How to read and interpret system log data
- How to identify suspicious patterns in authentication logs
- The importance of continuous monitoring in cybersecurity defense

---

*This project is part of my ongoing cybersecurity training and portfolio development.*
