# Suspicious Outbound RDP Connections 
### Description

Detects Non-Standard Tools Connecting to TCP port 3389 indicating possible lateral movement.

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

- Other Remote Desktop RDP tools

-------------------
### References

- https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2019-0708

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
