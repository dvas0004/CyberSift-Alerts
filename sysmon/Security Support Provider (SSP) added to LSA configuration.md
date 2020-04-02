# Security Support Provider (SSP) added to LSA configuration
### Description

Detects the addition of a SSP to the registry. Upon a reboot or API call, SSP DLLs gain access to encrypted and plaintext passwords stored in Windows. 

-------------------
### Severity

Critical

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

- Unlikely

-------------------
### References

- https://attack.mitre.org/techniques/T1101/
- https://powersploit.readthedocs.io/en/latest/Persistence/Install-SSP/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
