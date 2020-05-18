# Suspicious Driver Load from Temp
### Description

Detects a driver load from a temporary directory.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Triggers on Sysmon event Driver loaded (Event ID 6) where 'ImageLoaded' attribute fits '*\Temp\\*'

-------------------

### Possible causes of false positives

- there is a relevant set of false positives depending on applications in the environment 

-------------------
### References

- None

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
