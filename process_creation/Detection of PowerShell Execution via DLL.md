# Detection of PowerShell Execution via DLL
### Description

Detects PowerShell Strings applied to rundll as seen in PowerShdll.dll

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on rundll32.exe being used to run Powershell commands (via Powershdll.dll) with the following Powershell strings:
  - '*Default.GetString*'
  - '*FromBase64String*'

-------------------

### Possible causes of false positives



-------------------
### References

- https://github.com/p3nt4/PowerShdll/blob/master/README.md

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
