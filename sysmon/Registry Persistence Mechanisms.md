# Registry Persistence Mechanisms
### Description

Detects persistence registry keys .

-------------------
### Severity

Critical

-------------------
### Detailed Information

Target Objects: 
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
