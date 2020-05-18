# New RUN Key Pointing to Suspicious Folder
### Description

Detects suspicious new RUN key element pointing to an executable in a suspicious folder.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon Event 'RegistryEvent' (ID 13) where

TargetObject field in the Sysmon log entry is one of:
  - '*\SOFTWARE\Microsoft\Windows\CurrentVersion\Run\\*'
  - '*\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce\\*'
<br>AND<br> Details field is one of:
  - 'C:\Windows\Temp\\*'
  - '*\AppData\\*'
  - 'C:\$Recycle.bin\\*'
  - 'C:\Temp\\*'
  - 'C:\Users\Public\\*'
  - 'C:\Users\Default\\*'
  - 'C:\Users\Desktop\\*'

-------------------

### Possible causes of false positives

- Software with rare behaviour

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2018/08/fin7-pursuing-an-enigmatic-and-evasive-global-criminal-operation.html

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
