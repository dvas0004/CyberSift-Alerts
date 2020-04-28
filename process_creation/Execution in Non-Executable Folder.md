# Execution in Non-Executable Folder
### Description

Detects a suspicious exection from an uncommon folder.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on execution from one of the following directories:
  - '*\$Recycle.bin'
  - '*\Users\All Users\\*'
  - '*\Users\Default\\*'
  - '*\Users\Public\\*'
  - 'C:\Perflogs\\*'
  - '*\config\systemprofile\\*'
  - '*\Windows\Fonts\\*'
  - '*\Windows\IME\\*'
  - '*\Windows\addins\\*'

-------------------

### Possible causes of false positives

- Unkown

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
