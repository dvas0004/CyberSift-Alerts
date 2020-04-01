# Password Dumper Remote Thread in LSASS
### Description

Detects password dumper activity by monitoring remote thread creation EventID 8 in combination with the lsass.exe process as TargetImage. The process in field Process is the malicious program. A single execution can lead to hundreds of events.

-------------------
### Severity

High
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

- Unknown

-------------------
### References

- https://jpcertcc.github.io/ToolAnalysisResultSheet/details/WCE.htm

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
