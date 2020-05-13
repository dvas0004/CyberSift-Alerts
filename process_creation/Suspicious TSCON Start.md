# Suspicious TSCON Start
### Description

Detects a tscon.exe start as LOCAL SYSTEM.

-------------------
### Severity

- High

-------------------

### Detailed Information

Triggers on tscon.exe is run under NT_AUTHORITY\SYSTEM

-------------------

### Possible causes of false positives

- Unknown

-------------------
### References

    - http://www.korznikov.com/2017/03/0-day-or-feature-privilege-escalation.html
    - https://medium.com/@networksecurity/rdp-hijacking-how-to-hijack-rds-and-remoteapp-sessions-transparently-to-move-through-an-da2a1e73a5f6

-------------------
### Supported Log Sources

- Windows Process Creation

-------------------
