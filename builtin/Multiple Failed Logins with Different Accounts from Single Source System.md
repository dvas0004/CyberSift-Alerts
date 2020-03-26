# Multiple Failed Logins with Different Accounts from Single Source System
### Description

Detects suspicious failed logins with different user accounts from a single source system.

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

- Terminal servers
- Jump servers
- Other multiuser systems like Citrix server farms
- Workstations with frequently changing users

-------------------
### References

- None

-------------------
### Supported Log Sources

- windows security

-------------------
