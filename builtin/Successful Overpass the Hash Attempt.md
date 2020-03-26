# Successful Overpass the Hash Attempt
### Description

Detects successful logon with logon type 9 (NewCredentials) which matches the Overpass the Hash behavior of e.g Mimikatz's sekurlsa::pth module.

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

- Runas command-line tool using /netonly parameter

-------------------
### References

- https://cyberwardog.blogspot.de/2017/04/chronicles-of-threat-hunter-hunting-for.html

-------------------
### Supported Log Sources

- windows security

-------------------
