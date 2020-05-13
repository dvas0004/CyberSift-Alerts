# Suspicious XOR Encoded PowerShell Command Line
### Description

Detects suspicious powershell process which includes bxor command, alternative obfuscation method to b64 encoded commands.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

Triggers on a Powershell command fitting the pattern \* -bxor\*

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
