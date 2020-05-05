# Disable of ETW Trace
### Description

Detects a command that clears or disables any ETW trace log which could indicate a logging evasion.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on command line instructions fitting:
  - * cl */Trace*
  - * clear-log */Trace*
  - * sl* /e:false*
  - * set-log* /e:false*
  
-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

- https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/wevtutil
- https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mal_lockergoga.yml
- https://abuse.io/lockergoga.txt

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
