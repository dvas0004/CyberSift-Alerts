# Password Change on Directory Service Restore Mode (DSRM) Account
### Description

The Directory Service Restore Mode (DSRM) account is a local administrator account on Domain Controllers. Attackers may change the password to gain persistence.

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

- Initial installation of a domain controller

-------------------
### References

- https://adsecurity.org/?p=1714

-------------------
### Supported Log Sources

- windows security

-------------------
