# Elevate Labs Task 4 – Windows Firewall Configuration and Testing


# Task Overview:
The objective of this task was to configure and test basic firewall rules on a Windows system using the built-in Windows Defender Firewall with Advanced Security tool. This activity builds foundational knowledge in traffic filtering, rule-based access control, and system hardening.

## What I Did:
- Opened the firewall configuration tool using 'wf.msc'.
- Listed current inbound and outbound firewall rules.
- Created a new inbound rule to block TCP traffic on port 23 (Telnet).
- Tested the rule by attempting to connect to localhost on port 23 using Telnet.
- Observed and confirmed the connection was blocked as expected.
- Created another inbound rule to allow TCP traffic on port 22 (SSH), although typically used in Linux.
- Removed the test block rule to restore the system to its original state.
- Documented each step and captured screenshots of the firewall rule list, rule creation, Telnet test, and rule deletion.

## Key Learning:
- Windows Firewall uses inbound and outbound rules to control traffic.
- Rules can be based on port, protocol, application, and network profile.
- Blocking unused ports (like Telnet) helps reduce the system's attack surface.
- Traffic filtering works by matching packet properties against defined rules.

## Artifacts:
- screenshots/: Evidence of rule creation, rule testing, and rule deletion
- README.md: Summary of the task
