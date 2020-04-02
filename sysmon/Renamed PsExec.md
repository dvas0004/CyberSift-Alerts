# Renamed PsExec
### Description

Detects the execution of a renamed PsExec often used by attackers or malware. 

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

- Software that illegaly integrates PsExec in a renamed form
- Administrators that have renamed PsExec and no one knows why

-------------------
### References

- https://www.trendmicro.com/vinfo/hk-en/security/news/cybercrime-and-digital-threats/megacortex-ransomware-spotted-attacking-enterprise-networks

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
