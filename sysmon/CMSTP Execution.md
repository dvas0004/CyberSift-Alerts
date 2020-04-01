# CMSTP Execution
### Description

Detects various indicators of Microsoft Connection Manager Profile Installer execution.

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

- Legitimate CMSTP use (unlikely in modern enterprise environments)

-------------------
### References

- http://www.endurant.io/cmstp/detecting-cmstp-enabled-code-execution-and-uac-bypass-with-sysmon/

-------------------
### Supported Log Sources

- Windows Sysmon
- Windows Process Creation

-------------------
