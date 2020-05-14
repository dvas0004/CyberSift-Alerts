# Suspicious Parent of Csc.exe
### Description

Detects a suspicious parent of csc.exe, which could by a sign of payload delivery.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on csc.exe running with wscript.exe, cscript.exe, mshta.exe

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://twitter.com/SBousseaden/status/1094924091256176641

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
