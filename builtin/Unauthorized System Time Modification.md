# Unauthorized System Time Modification
### Description

Detect scenarios where a potentially unauthorized application or user is modifying the system time.

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

- HyperV or other virtualization technologies with binary not listed in filter portion of detection

-------------------
### References

- Private Cuckoo Sandbox (from many years ago, no longer have hash, NDA as well)
- Live environment caused by malware

-------------------
### Supported Log Sources

- windows security

-------------------
