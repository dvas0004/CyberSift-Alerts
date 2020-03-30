# PowerShell Downgrade Attack
### Description

Detects PowerShell downgrade attack by comparing the host versions with the actually used engine version 2.0

-------------------
### Severity

- Medium

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

- Penetration Test
- Unknown

-------------------
### References

- http://www.leeholmes.com/blog/2017/03/17/detecting-and-preventing-powershell-downgrade-attacks/

-------------------
### Supported Log Sources

- Windows Powershell Classic

-------------------
