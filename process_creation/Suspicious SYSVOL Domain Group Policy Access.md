# Suspicious SYSVOL Domain Group Policy Access
### Description

Detects Access to Domain Group Policies stored in SYSVOL.

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

- administrative activity

-------------------
### References

 - https://adsecurity.org/?p=2288
 - https://www.hybrid-analysis.com/sample/f2943f5e45befa52fb12748ca7171d30096e1d4fc3c365561497c618341299d5?environmentId=100

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
