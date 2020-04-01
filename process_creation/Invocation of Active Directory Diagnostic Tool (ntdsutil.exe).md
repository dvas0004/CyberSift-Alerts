# Invocation of Active Directory Diagnostic Tool (ntdsutil.exe)
### Description

Detects execution of ntdsutil.exe, which can be used for various attacks against the NTDS database (NTDS.DIT).

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

- NTDS maintenance

-------------------
### References

- https://jpcertcc.github.io/ToolAnalysisResultSheet/details/ntdsutil.htm

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
