# Ransomware Deleting Shadow Volume Copies
### Description

Detects a command that deletes all local shadow volume copies as often used by Ransomware.

-------------------
### Severity

Critical

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

- Adminsitrative scripts - e.g. to prepare image for golden image creation

-------------------
### References

- https://www.hybrid-analysis.com/sample/ed01ebfbc9eb5bbea545af4d01bf5f1071661840480439c6e5babe8e080e41aa?environmentId=100

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
