# WMI Persistence - Script Event Consumer
### Description

Detects WMI script event consumers

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on sdbinst.exe run with parameters fitting '*\AppPatch\\*}.sdb*'

-------------------

### Possible causes of false positives

- Legitimate event consumers

-------------------
### References

- https://www.eideon.com/2018-03-02-THL03-WMIBackdoors/

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
