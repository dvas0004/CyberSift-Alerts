# Rare Scheduled Task Creations
### Description

This rule detects rare scheduled task creations. Typically software gets installed on multiple systems and not only on a few. 
The aggregation and count function selects tasks with rare names.

-------------------
### Severity

- Low

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

- Software installation

-------------------
### References

- None

-------------------
### Supported Log Sources

- windows task scheduler

-------------------
