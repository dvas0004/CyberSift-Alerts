# Sticky Key Like Backdoor Usage
### Description

Detects the usage and installation of a backdoor that uses an option to register a malicious debugger for built-in tools that are accessible in the login screen.

-------------------
### Severity

Critical

-------------------

### Detailed Information

Triggers on Sysmon Event RegistryEvent (Value Set) (ID 13) where 'TargetObject' attribute has value fitting one of the following wildcard patterns:
  - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\sethc.exe\Debugger'
  - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\utilman.exe\Debugger'
  - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\osk.exe\Debugger'
  - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\Magnify.exe\Debugger'
  - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\Narrator.exe\Debugger'
  - '*\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\DisplaySwitch.exe\Debugger'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://blogs.technet.microsoft.com/jonathantrull/2016/10/03/detecting-sticky-key-backdoors/

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
