# WMI Spawning Windows PowerShell
### Description

Detects WMI spawning PowerShell

-------------------
### Severity

High

-------------------
<!---
### Detailed Information

- Why is this alert triggered?
- What are the typical causes that generate this alert? (e.g. port scans, unusual file access activity, etc...)
- Which corroborating information should be looked up?
- Any supporting queries to get more information?
- Any supporting visualizations to get more information?

-------------------
--->
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
