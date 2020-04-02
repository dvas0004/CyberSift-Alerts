# New RUN Key Pointing to Suspicious Folder
### Description

Detects suspicious new RUN key element pointing to an executable in a suspicious folder.

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

- Software with rare behaviour

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2018/08/fin7-pursuing-an-enigmatic-and-evasive-global-criminal-operation.html

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
