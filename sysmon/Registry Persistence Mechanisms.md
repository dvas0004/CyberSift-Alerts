# Registry Persistence Mechanisms
### Description

Detects persistence registry keys .

-------------------
### Severity

Critical

-------------------
### Detailed Information
Triggers on Sysmon event RegistryEvent (Value Set) (ID 13) where 'TargetObject' event attribute (the Registry key being set) fits one of the wildcard patterns:
  - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\\*\GlobalFlag'
  - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\SilentProcessExit\\*\ReportingMode'
  - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\SilentProcessExit\\*\MonitorProcess'

-------------------
### Possible causes of false positives

- Unknown

-------------------
### References

- https://oddvar.moe/2018/04/10/persistence-using-globalflags-in-image-file-execution-options-hidden-from-autoruns-exe/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
