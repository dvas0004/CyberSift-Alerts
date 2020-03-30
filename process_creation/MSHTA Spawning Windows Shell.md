# MSHTA Spawning Windows Shell
### Description

Detects a Windows command line executable started from MSHTA.

-------------------
### Severity

- High

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

- Printer software / driver installations
- HP software

-------------------
### References

- https://www.trustedsec.com/july-2015/malicious-htas/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
