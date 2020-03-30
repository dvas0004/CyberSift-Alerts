# Cmdkey Cached Credentials Recon
### Description

Detects usage of cmdkey to look for cached credentials.

-------------------
### Severity

- Low

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

=> What could cause this alert to mistakenly get generated? For example: <=
- Joining a PC to a domain
- Large file upload
- Shared infrastructure (CDN)

-------------------
### References

- Legitimate administrative tasks.

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
