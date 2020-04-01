# PowerShell Script Run in AppData
### Description

Detects a suspicious command line execution that invokes PowerShell with reference to an AppData folder.

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

- Administrative scripts

-------------------
### References

- https://twitter.com/JohnLaTwC/status/1082851155481288706
- https://app.any.run/tasks/f87f1c4e-47e2-4c46-9cf4-31454c06ce03

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
