# Suspicious Certutil Command
### Description

Detects a suspicious Microsoft certutil execution with sub commands like 'decode' sub command, which is sometimes used to decode malicious code with
the built-in certutil utility.

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

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- https://twitter.com/JohnLaTwC/status/835149808817991680
- https://twitter.com/subTee/status/888102593838362624
- https://twitter.com/subTee/status/888071631528235010
- https://blogs.technet.microsoft.com/pki/2006/11/30/basic-crl-checking-with-certutil/
- https://www.trustedsec.com/2017/07/new-tool-release-nps_payload/
- https://twitter.com/egre55/status/1087685529016193025
- https://lolbas-project.github.io/lolbas/Binaries/Certutil/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
