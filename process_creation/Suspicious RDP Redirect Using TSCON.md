# Suspicious RDP Redirect Using TSCON
### Description

Detects a suspicious RDP session redirect using tscon.exe

-------------------
### Severity

High

-------------------

### Detailed Information

Triggers on command fitting wildcard pattern:
  - \* /dest:rdp-tcp:\*

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
