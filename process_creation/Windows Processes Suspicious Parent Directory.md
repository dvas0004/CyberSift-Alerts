# Windows Processes Suspicious Parent Directory
### Description

Detect suspicious parent processes of well-known Windows processes

-------------------
### Severity

Low

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

- Some security products seem to spawn these

-------------------
### References

- https://securitybytes.io/blue-team-fundamentals-part-two-windows-processes-759fe15965e2
- https://www.carbonblack.com/2014/06/10/screenshot-demo-hunt-evil-faster-than-ever-with-carbon-black/
- https://www.13cubed.com/downloads/windows_process_genealogy_v2.pdf
- https://attack.mitre.org/techniques/T1036/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
