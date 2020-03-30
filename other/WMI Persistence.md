# WMI Persistence
### Description

Detects suspicious WMI event filter and command line event consumer based on event id 5861 and 5859 (Windows 10, 2012 and higher)

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

- Unknown (data set is too small; further testing needed)

-------------------
### References

- https://twitter.com/mattifestation/status/899646620148539397
- https://www.eideon.com/2018-03-02-THL03-WMIBackdoors/

-------------------
### Supported Log Sources

- windows wmi

-------------------
