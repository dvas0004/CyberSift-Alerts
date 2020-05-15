# Windows 10 scheduled task SandboxEscaper 0-day
### Description

Detects Task Scheduler .job import arbitrary DACL write\par.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on schtasks.exe being run with the following parameters:
  - /change
  - /TN
  - /RU
  - /RP

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://github.com/SandboxEscaper/polarbearrepo/tree/master/bearlpe

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
