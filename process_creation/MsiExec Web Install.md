# MsiExec Web Install
### Description

Detects suspicious msiexec process starts with web addreses as parameter.

-------------------
### Severity

Medium

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

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- https://blog.trendmicro.com/trendlabs-security-intelligence/attack-using-windows-installer-msiexec-exe-leads-lokibot/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
