# Admin User Remote Logon
### Description

Detect remote login by Administrator user depending on internal pattern

-------------------
### Severity

Low

-------------------

### Detailed Information

A remote desktop logon, through RDP, may be typical of a system administrator or IT support, but only from select workstations. Monitoring remote desktop logons and comparing to known/approved originating systems can detect lateral movement of an adversary.

-------------------
### Possible causes of false positives

- Legitimate administrative activity

-------------------

### References

- https://car.mitre.org/wiki/CAR-2016-04-005

-------------------
### Supported Log Sources

=> Insert supported log sources here, for example: <=
- windows application
- windows security
- firewall

-------------------
