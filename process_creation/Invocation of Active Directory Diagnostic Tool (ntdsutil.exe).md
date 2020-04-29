# Invocation of Active Directory Diagnostic Tool (ntdsutil.exe)
### Description

Detects execution of ntdsutil.exe, which can be used for various attacks against the NTDS database (NTDS.DIT).

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on command line:
  - \*\ntdsutil\*

-------------------

### Possible causes of false positives

- NTDS maintenance

-------------------
### References

- https://jpcertcc.github.io/ToolAnalysisResultSheet/details/ntdsutil.htm

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
