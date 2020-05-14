# Suspicious GUP Usage
### Description

Detects execution of the Notepad++ updater in a suspicious directory, which is often used in DLL side-loading attacks.

-------------------
### Severity

High

-------------------

### Detailed Information
Triggers on gup.exe running from any directory other than those below:
  - 'C:\Users\*\AppData\Local\Notepad++\updater\gup.exe'
  - 'C:\Users\*\AppData\Roaming\Notepad++\updater\gup.exe'
  - 'C:\Program Files\Notepad++\updater\gup.exe'
  - 'C:\Program Files (x86)\Notepad++\updater\gup.exe'

-------------------

### Possible causes of false positives

- Execution of tools named GUP.exe and located in folders different than Notepad++\updater

-------------------
### References

- https://www.fireeye.com/blog/threat-research/2018/09/apt10-targeting-japanese-corporations-using-updated-ttps.html

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
