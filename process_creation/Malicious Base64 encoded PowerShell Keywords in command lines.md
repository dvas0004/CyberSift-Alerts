# Malicious Base64 encoded PowerShell Keywords in command lines
### Description

Detects base64 encoded strings used in hidden malicious PowerShell command lines

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

- Penetration Tests

-------------------
### References

- http://www.leeholmes.com/blog/2017/09/21/searching-for-content-in-base-64-strings/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
