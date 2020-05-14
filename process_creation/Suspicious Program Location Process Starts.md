# Suspicious Program Location Process Starts
### Description

Detects programs running in suspicious files system locations.

-------------------
### Severity

High

-------------------

### Detailed Information
Triggers when a process is launched from a path fitting one of the following wildcard patterns:
  - '*\$Recycle.bin'
  - '*\Users\Public\\*'
  - 'C:\Perflogs\\*'
  - '*\Windows\Fonts\\*'
  - '*\Windows\IME\\*'
  - '*\Windows\addins\\*'
  - '*\Windows\debug\\*'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://docs.google.com/spreadsheets/d/17pSTDNpa0sf6pHeRhusvWG6rThciE8CsXTSlDUAZDyo

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
