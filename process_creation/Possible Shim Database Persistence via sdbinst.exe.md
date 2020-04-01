# Possible Shim Database Persistence via sdbinst.exe
### Description

Detects execution of sdbinst writing to default shim database path C:\Windows\AppPatch\*

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

- Unknown

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2017/05/fin7-shim-databases-persistence.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
