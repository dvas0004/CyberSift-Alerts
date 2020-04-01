# Windows Shell Spawning Suspicious Program
### Description

Detects a suspicious child process of a Windows shell.

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

- Administrative scripts
- Microsoft SCCM

-------------------
### References

- https://mgreen27.github.io/posts/2018/04/02/DownloadCradle.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
