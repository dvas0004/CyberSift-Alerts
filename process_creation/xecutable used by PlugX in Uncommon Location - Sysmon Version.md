# Executable used by PlugX in Uncommon Location - Sysmon Version
### Description

Detects the execution of an executable that is typically used by PlugX for DLL side loading started from an uncommon location

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

- http://www.hexacorn.com/blog/2016/03/10/beyond-good-ol-run-key-part-36/
- https://countuponsecurity.com/2017/06/07/threat-hunting-in-the-enterprise-with-appcompatprocessor/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
