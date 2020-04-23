# Rare Scheduled Task Creations
### Description

This rule detects rare scheduled task creations. Typically software gets installed on multiple systems and not only on a few. 
The aggregation and count function selects tasks with rare names.

-------------------
### Severity

- Low

-------------------

### Detailed Information

Events:
  - 106 General Task Registration

Triggers on detection of the above event for the same Task name 5 times or more within a 7 day period.

-------------------

### Possible causes of false positives

- Software installation

-------------------
### References

- None

-------------------
### Supported Log Sources

- windows task scheduler

-------------------
