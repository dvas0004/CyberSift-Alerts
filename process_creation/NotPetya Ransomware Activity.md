# NotPetya Ransomware Activity
### Description

Detects NotPetya ransomware activity in which the extracted passwords are passed back to the main module via named pipe, the file system journal of drive
C is deleted and windows eventlogs are cleared using wevtutil.

-------------------
### Severity

- Critical

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

- Admin activity

-------------------
### References

- https://securelist.com/schroedingers-petya/78870/
- https://www.hybrid-analysis.com/sample/64b0b58a2c030c77fdb2b537b2fcc4af432bc55ffb36599a31d418c7c69e94b1?environmentId=100

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
