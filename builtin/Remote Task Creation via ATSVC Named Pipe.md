# Remote Task Creation via ATSVC named pipe
### Description

Detects remote task creation via at.exe or API interacting with ATSVC namedpipe.

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

- pentesting

-------------------
### References

- https://blog.menasec.net/2019/03/threat-hunting-25-scheduled-tasks-for.html

-------------------
### Supported Log Sources

- windows security

-------------------
