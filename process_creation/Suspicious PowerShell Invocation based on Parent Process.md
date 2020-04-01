# Suspicious PowerShell Invocation based on Parent Process
### Description

Detects suspicious powershell invocations from interpreters or unusual programs.

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

- Microsoft Operations Manager (MOM)
- Other scripts

-------------------
### References

- https://www.carbonblack.com/2017/03/15/attackers-leverage-excel-powershell-dns-latest-non-malware-attack/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
