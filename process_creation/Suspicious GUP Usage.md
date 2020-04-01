# Suspicious GUP Usage
### Description

Detects execution of the Notepad++ updater in a suspicious directory, which is often used in DLL side-loading attacks.

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

- Execution of tools named GUP.exe and located in folders different than Notepad++\updater

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2018/09/apt10-targeting-japanese-corporations-using-updated-ttps.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
