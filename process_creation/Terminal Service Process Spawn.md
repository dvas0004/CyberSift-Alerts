# Terminal Service Process Spawn
### Description

Detects a process spawned by the terminal service server process (this could be an indicator for an exploitation of CVE-2019-0708)

-------------------
### Severity

- High

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

- https://securingtomorrow.mcafee.com/other-blogs/mcafee-labs/rdp-stands-for-really-do-patch-understanding-the-wormable-rdp-vulnerability-cve-2019-0708/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
