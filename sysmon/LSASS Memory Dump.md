# LSASS Memory Dump
### Description

Detects process LSASS memory dump using procdump or taskmgr based on the CallTrace pointing to dbghelp.dll or dbgcore.dll for win10.

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on Sysmon event ProcessAccess (Event ID 10) where the process accessed is lsass.exe

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://blog.menasec.net/2019/02/threat-hunting-21-procdump-or-taskmgr.html

-------------------
### Supported Log Sources

- Windows Sysmon

-------------------
