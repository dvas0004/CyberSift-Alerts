# Usage of Sysinternals Tools
### Description

Detects the usage of Sysinternals Tools due to accepteula key beeing added to Registry.

-------------------
### Severity

Low

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

- Legitimate use of SysInternals tools
- Programs that use the same Registry Key

-------------------
### References

- https://twitter.com/Moti_B/status/1008587936735035392

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
