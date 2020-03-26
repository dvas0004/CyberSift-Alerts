# Disabling Windows Event Auditing
### Description

Detects scenarios where system auditing (ie: windows event log auditing) is disabled. This may be used in a scenario
where an entity would want to bypass local logging to evade detection when windows event logging is enabled and
reviewed. Also, it is recommended to turn off "Local Group Policy Object Processing" via GPO, which will make sure
that Active Directory GPOs take precedence over local/edited computer policies via something such as "gpedit.msc".
Please note, that disabling "Local Group Policy Object Processing" may cause an issue in scenarios of one off
specific GPO modifications -- however it is recommended to perform these modifications in Active Directory anyways.

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

Unknown

-------------------
### References

- https://bit.ly/WinLogsZero2Hero
 
-------------------
### Supported Log Sources

- windows security

-------------------
