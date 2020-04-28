# Dridex Process Pattern
### Description

Detects typical Dridex process patterns.

-------------------
### Severity

- Critical

-------------------

### Detailed Information

Triggers on the following command line patterns:
  - *\svchost.exe C:\Users\\*\Desktop\\*

or

  - '*whoami.exe /all'
  - '*net.exe view'

Having svchost.exe as a parent process.

-------------------

### Possible causes of false positives

- Unlikely, unknown.

-------------------
### References

- https://app.any.run/tasks/993daa5e-112a-4ff6-8b5a-edbcec7c7ba3

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
