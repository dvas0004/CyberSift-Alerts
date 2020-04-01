# Executable in ADS
### Description

Detects the creation of an ADS data stream that contains an executable (non-empty imphash).

-------------------
### Severity

Critical

-------------------
### Detailed Information
<!---
- Why is this alert triggered?
- What are the typical causes that generate this alert? (e.g. port scans, unusual file access activity, etc...)
- Which corroborating information should be looked up?
- Any supporting queries to get more information?
- Any supporting visualizations to get more information?
--->
Requires Sysmon config with Imphash logging activated.

-------------------
### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/0xrawsec/status/1002478725605273600?s=21

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
