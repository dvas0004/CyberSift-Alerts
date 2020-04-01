# Possible Ransomware or unauthorized MBR modifications
### Description

Detects, possibly, malicious unauthorized usage of bcdedit.exe

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

- Unknown

-------------------
### References

- https://docs.microsoft.com/en-us/windows-hardware/drivers/devtest/bcdedit--set

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
