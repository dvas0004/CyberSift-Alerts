# CACTUSTORCH Remote Thread Creation
### Description

Detects remote thread creation from CACTUSTORCH as described in references.

-------------------
### Severity

High

-------------------

### Detailed Information
Triggers on a process being launched from \*\SysWOW64\\\* by one of the following processes.

  - '*\System32\cscript.exe'
  - '*\System32\wscript.exe'
  - '*\System32\mshta.exe'
  - '*\winword.exe'
  - '*\excel.exe'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/SBousseaden/status/1090588499517079552
- https://github.com/mdsecactivebreach/CACTUSTORCH

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
