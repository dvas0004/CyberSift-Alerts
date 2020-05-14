# Suspicious Encoded PowerShell Command Line
### Description

Detects suspicious powershell process starts with base64 encoded commands.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on base64 encoded commands starting with the following base64 encoded strings:
  - JAB
  - SUVYI
  - aWV4I
  - SQBFAFgA
  - aQBlAHgA

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://app.any.run/tasks/6217d77d-3189-4db2-a957-8ab239f3e01e

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
