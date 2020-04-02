# WMI Event Subscription
### Description

Detects creation of WMI event subscription persistence method.

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

- exclude legitimate (vetted) use of WMI event subscription in your network

-------------------
### References

- https://attack.mitre.org/techniques/T1084/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
