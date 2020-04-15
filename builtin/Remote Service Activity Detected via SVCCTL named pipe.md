# Remote Service Activity Detected via SVCCTL named pipe
### Description

Detects remote remote service activity via remote access to the svcctl named pipe.

-------------------
### Severity

- Medium

-------------------

### Detailed Information

Events:
  - 5145 A network share object was checked to see whether client can be granted desired access

Fires where share name fits the format: '\\*\IPC$'
and target name is: 'svcctl'

-------------------

### Possible causes of false positives

- Pentesting

-------------------
### References

- https://blog.menasec.net/2019/03/threat-hunting-26-remote-windows.html

-------------------
### Supported Log Sources

- windows security

-------------------
