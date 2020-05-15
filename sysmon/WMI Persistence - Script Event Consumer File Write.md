# WMI Persistence - Script Event Consumer File Write
### Description

Detects file writes of WMI script event consumer

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers when C:\WINDOWS\system32\wbem\scrcons.exe writes a file.

-------------------

### Possible causes of false positives

- Unknown (data set is too small; further testing needed)

-------------------
### References

- https://www.eideon.com/2018-03-02-THL03-WMIBackdoors/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
