# PowerShell ShellCode
### Description

Detects Base64 encoded Shellcode.

-------------------
### Severity

- Critical

-------------------

### Detailed Information

Event
  - 4104 Execute Remote Command
  
 Triggers on the following Base64 sequences:
  - '*AAAAYInlM*'
  - '*OiCAAAAYInlM*'
  - '*OiJAAAAYInlM*'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/cyb3rops/status/1063072865992523776

-------------------
### Supported Log Sources

- Windows Powershell

-------------------
