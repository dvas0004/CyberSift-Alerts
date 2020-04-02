# RDP over Reverse SSH Tunnel
### Description

Detects svchost hosting RDP termsvcs communicating with the loopback address and on TCP port 3389.

-------------------
### Severity

High

-------------------
<!---
### Detailed Information

- Why is this alert triggered?
- What are the typical causes that generate this alert? (e.g. port scans, unusual file access activity, etc...)
- Which corroborating information should be looked up?
- Any supporting queries to get more information?
- Any supporting visualizations to get more information?

-------------------
--->
### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/SBousseaden/status/1096148422984384514

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
