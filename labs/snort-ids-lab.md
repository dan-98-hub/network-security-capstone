# Snort IDS Configuration Lab

## Objective
Configure intrusion detection rules to monitor suspicious activity within a test environment.

## Tools Used
- Snort
- Kali Linux

## Sample Rule
```txt
alert tcp any any -> any 80 (msg:"HTTP Traffic Detected"; sid:1000001;)
```

## Outcome
Successfully generated alerts based on simulated network traffic and improved understanding of intrusion detection workflows.
