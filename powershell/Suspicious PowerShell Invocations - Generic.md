# Suspicious PowerShell Invocations - Generic
### Description

Detects suspicious PowerShell invocation command parameters.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on the following Powershell invocation parameters:
  - ' -enc '
  - ' -EncodedCommand '
  - ' -w hidden '
  - ' -window hidden '
  - ' - windowstyle hidden '
  - ' -noni '
  - ' -noninteractive '

-------------------

### Possible causes of false positives

- Penetration tests
- Very special / sneaky PowerShell scripts

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Powershell

-------------------
