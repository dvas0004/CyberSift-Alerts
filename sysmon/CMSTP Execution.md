# CMSTP Execution
### Description

Detects various indicators of Microsoft Connection Manager Profile Installer execution.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on cmmgr32.exe added to a new or existing registry value or a process accessing cmlua.dll.

-------------------

### Possible causes of false positives

- Legitimate CMSTP use (unlikely in modern enterprise environments)

-------------------
### References

- http://www.endurant.io/cmstp/detecting-cmstp-enabled-code-execution-and-uac-bypass-with-sysmon/

-------------------
### Supported Log Sources

- Windows Sysmon
- Windows Process Creation

-------------------
