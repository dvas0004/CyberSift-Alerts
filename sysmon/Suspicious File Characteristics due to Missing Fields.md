# Suspicious File Characteristics due to Missing Fields
### Description

Detects Executables without FileVersion,Description,Product,Company likely created with py2exe.

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

- https://securelist.com/muddywater/88059/
- https://www.virustotal.com/#/file/276a765a10f98cda1a38d3a31e7483585ca3722ecad19d784441293acf1b7beb/detection

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
