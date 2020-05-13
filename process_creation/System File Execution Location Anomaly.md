# System File Execution Location Anomaly
### Description

Detects a Windows program executable started in a suspicious folder.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on:
  - '*\svchost.exe'
  - '*\rundll32.exe'
  - '*\services.exe'
  - '*\powershell.exe'
  - '*\regsvr32.exe'
  - '*\spoolsv.exe'
  - '*\lsass.exe'
  - '*\smss.exe'
  - '*\csrss.exe'
  - '*\conhost.exe'
  - '*\wininit.exe'
  - '*\lsm.exe'
  - '*\winlogon.exe'
  - '*\explorer.exe'
  - '*\taskhost.exe' 

Being run from a folder other than:
  - 'C:\Windows\System32\\*'
  - 'C:\Windows\SysWow64\\*'
  - 'C:\Windows\explorer.exe'
  - 'C:\Windows\winsxs\*'
  
-------------------

### Possible causes of false positives

- Exotic software

-------------------
### References

- https://twitter.com/GelosSnake/status/934900723426439170

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
