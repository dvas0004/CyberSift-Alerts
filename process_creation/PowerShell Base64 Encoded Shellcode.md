# PowerShell Base64 Encoded Shellcode
### Description

Detects Base64 encoded Shellcode

-------------------
### Severity

- Critical

-------------------

### Detailed Information

Triggers on detection of the base64 string 'AAAAYInlM' along with either 'OiCAAAAYInlM' or 'OiJAAAAYInlM'

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/cyb3rops/status/1063072865992523776

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
