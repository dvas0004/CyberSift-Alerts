# Suspicious Svchost Process
### Description

Detects a suspicious svchost process start.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on svchost.exe being started from any process other than:

  - services.exe
  - MsMpEng.exe
  - Mrt.exe
  - rpcnet.exe

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
