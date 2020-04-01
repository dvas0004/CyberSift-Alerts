# Reconnaissance Activity with Net Command
### Description

Detects a set of commands often used in recon stages by different attack groups.

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

- False positives depend on scripts and administrative tools used in the monitored environment

-------------------
### References

- https://twitter.com/haroonmeer/status/939099379834658817
- https://twitter.com/c_APT_ure/status/939475433711722497
- https://www.fireeye.com/blog/threat-research/2016/05/targeted_attacksaga.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
