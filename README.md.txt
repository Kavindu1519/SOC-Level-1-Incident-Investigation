# SOC Level 1 Incident Investigation Project

## Project Overview
This project simulates a SOC Level 1 incident investigation using Windows Event Logs.  
The objective was to detect and analyze suspicious authentication activity and post-login behavior on a Windows host.

## Scenario
Multiple failed login attempts followed by a successful login were observed on a Windows system, indicating a potential brute-force attack.

## Tools & Technologies
- Windows 10
- Windows Event Viewer
- Security Event Logs

## Event IDs Investigated
- 4625 – Failed logon attempt
- 4624 – Successful logon
- 4688 – Process creation

## Investigation Steps
1. Enabled Windows audit policies
2. Generated failed and successful login events
3. Analyzed security logs using Event Viewer
4. Correlated events to identify attack patterns
5. Documented findings in an incident report

## Outcome
The investigation identified a possible brute-force login attempt followed by suspicious command execution activity.

## Skills Demonstrated
- Security log analysis
- Incident triage
- Event correlation
- SOC documentation
