# Possible Ransomware or unauthorized MBR modifications
### Description

Detects, possibly, malicious unauthorized usage of bcdedit.exe

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on running of bcdedit.exe with parameters:
  - delete
  - deletevalue
  - import

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://docs.microsoft.com/en-us/windows-hardware/drivers/devtest/bcdedit--set

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
