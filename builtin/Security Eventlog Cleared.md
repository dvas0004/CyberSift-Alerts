# Security Eventlog Cleared
### Description

Some threat groups tend to delete the local 'Security' Eventlog using certain utitlities.

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

- Rollout of log collection agents (the setup routine often includes a reset of the local Eventlog)
- System provisioning (system reset before the golden image creation)

-------------------
### References

- None
-------------------
### Supported Log Sources

- windows security

-------------------
