# WMI Spawning Windows PowerShell
### Description

Detects WMI spawning PowerShell

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on powershell.exe being run with wmiprvse.exe as parent process.

-------------------

### Possible causes of false positives

- AppvClient
- CCM

-------------------
### References

- https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shell_spawn_susp_program.yml
- https://any.run/report/68bc255f9b0db6a0d30a8f2dadfbee3256acfe12497bf93943bc1eab0735e45e/a2385d6f-34f7-403c-90d3-b1f9d2a90a5e

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
