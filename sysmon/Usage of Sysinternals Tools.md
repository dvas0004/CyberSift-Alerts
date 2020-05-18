# Usage of Sysinternals Tools
### Description

Detects the usage of Sysinternals Tools due to accepteula key beeing added to Registry.

-------------------
### Severity

Low

-------------------

### Detailed Information

Triggers on Sysmon Event with ID 13 (RegistryEvent) where registry key 'EulaAccepted' is set.

-------------------

### Possible causes of false positives

- Legitimate use of SysInternals tools
- Programs that use the same Registry Key

-------------------
### References

- https://twitter.com/Moti_B/status/1008587936735035392

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
