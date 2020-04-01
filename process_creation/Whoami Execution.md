# Whoami Execution
### Description

Detects the execution of whoami, which is often used by attackers after exloitation / privilege escalation but rarely used by administrators.

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

- Admin activity
- Scripts and administrative tools used in the monitored environment

-------------------
### References

- https://twitter.com/haroonmeer/status/939099379834658817
- https://twitter.com/c_APT_ure/status/939475433711722497

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
