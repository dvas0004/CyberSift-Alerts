# Remote Task Creation via ATSVC named pipe
### Description

Detects remote task creation via at.exe or API interacting with ATSVC namedpipe.

-------------------
### Severity

Medium

-------------------

### Detailed Information

Events:
  - 5145 A network share object was checked to see whether client can be granted desired access

Triggers where accessed share path fits the format: '\\*\IPC$' 
and target name is 'atvsc', and Write access is requested.

-------------------

### Possible causes of false positives

- pentesting

-------------------
### References

- https://blog.menasec.net/2019/03/threat-hunting-25-scheduled-tasks-for.html

-------------------
### Supported Log Sources

- windows security

-------------------
