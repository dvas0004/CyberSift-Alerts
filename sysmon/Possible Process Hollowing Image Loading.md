# Possible Process Hollowing Image Loading
### Description

Detects Loading of samlib.dll, WinSCard.dll from untypical process e.g. through process hollowing by Mimikatz.

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

- Very likely, needs more tuning

-------------------
### References

- https://cyberwardog.blogspot.com/2017/03/chronicles-of-threat-hunter-hunting-for.html

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
