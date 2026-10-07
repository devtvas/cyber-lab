# SOC Lab Methodology

The Cyber Lab follows an analyst-oriented workflow.

## 1. Define the objective

Start with a concrete security question.

Example:

> How can suspicious SSH authentication activity be detected and triaged?

## 2. Build a controlled environment

Use local VMs, containers, intentionally vulnerable applications or other explicitly authorized environments.

## 3. Generate or collect evidence

Record:

- logs;
- alerts;
- timestamps;
- source/destination;
- usernames;
- processes;
- IPs;
- domains;
- hashes, when relevant;
- commands;
- screenshots or sanitized outputs.

Never commit credentials, secrets, private tokens or personal data.

## 4. Triage

Determine:

- Is the event suspicious?
- Is it a false positive?
- What asset is affected?
- What user/process is involved?
- What is the potential impact?
- What additional evidence is required?

## 5. Investigate

Build a timeline and correlate available evidence.

Look for:

- repeated behavior;
- related authentication events;
- process activity;
- network connections;
- IOCs;
- persistence indicators;
- lateral movement indicators.

## 6. Classify

When appropriate, document:

- severity;
- confidence;
- affected asset;
- incident category;
- MITRE ATT&CK technique.

## 7. Respond

For laboratory scenarios, document appropriate defensive actions such as:

- blocking;
- isolating;
- disabling a test account;
- terminating a malicious process;
- removing persistence;
- patching;
- changing configuration.

## 8. Report

Every investigation should produce a concise analyst report:

- Executive summary
- Timeline
- Evidence
- Analysis
- Impact
- MITRE mapping
- Response
- Recommendations
- Lessons learned

## 9. Review

Ask:

- Could the alert have been detected earlier?
- Was the alert too noisy?
- What additional telemetry would help?
- Could part of the response be automated?

The goal is to demonstrate **security reasoning**, not simply tool usage.
