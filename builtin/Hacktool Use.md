# Hacktool Use
### Description

This method detects well-known keywords.
Certain field combination that appear in Windows Eventlog when certain hack tools are used

-------------------
### Severity

- Critical

### Detailed Information

Looks for the following event IDs in the Windows Event Logs to identify the "Ruler" attack tool:
  - 4776
  - 4624
  - 4625


### Possible causes of false positives

Unknown

-------------------
### References

None

-------------------
### Supported Log Sources

- windows security

-------------------
