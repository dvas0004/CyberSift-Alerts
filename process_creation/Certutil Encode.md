# Certutil Encode
### Description

Detects suspicious a certutil command that used to encode files, which is sometimes used for data exfiltration.

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

- Unknown

-------------------
### References

- https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/certutil
- https://unit42.paloaltonetworks.com/new-babyshark-malware-targets-u-s-national-security-think-tanks/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
