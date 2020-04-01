# Execution in Webserver Root Folder
### Description

Detects a suspicious program execution in a web service root folder (filter out false positives).

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

- Various applications
- Tools that include ping or nslookup command invocations

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
