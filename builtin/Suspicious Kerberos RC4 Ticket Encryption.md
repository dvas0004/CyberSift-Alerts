# Suspicious Kerberos RC4 Ticket Encryption
### Description

Detects service ticket requests using RC4 encryption type.

-------------------
### Severity

- Medium

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

- Service accounts used on legacy systems (e.g. NetApp)
- Windows Domains with DFL 2003 and legacy systems

-------------------
### References

- https://adsecurity.org/?p=3458
- https://www.trimarcsecurity.com/single-post/TrimarcResearch/Detecting-Kerberoasting-Activity

-------------------
### Supported Log Sources

- windows security

-------------------
